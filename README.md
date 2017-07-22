# graphql-build-issue-16-repro
Repro for issue 16 postgraphql/graphql-build

Run each of the three 2-line scripts in sequence and confirm the results at each script:
* `1-init-working`  Creates a database and demonstrates postgraphql working
* `2-break-with-extension`  Installs the `tablefunc` extension and shows the postgraphql error that it causes.
* `3-remove-extension-working-again`  Removes the extension and shows postgraphql working again.
