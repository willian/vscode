# VSCODE

My vscode configuration:

* [extensions](./extensions.md)
* [settings](./settings.json)

To run ruby tests in docker containers using docket-compose I use the following script.

* [docker-compose-run-spec](./docker-compose-run-spec)

It will try to find a service in your docker-compose.yml file called `app`, `api` or `test` and use it to run your tests.
Put that script in any folder included in your $PATH and it will work.