## Franklin - example of user website

### Notes

**Repo setup**

* Generate keys with `ssh-keygen -N "" -f franklin`
* Add the content of `franklin` to a new _secret_ of the repository named `FRANKLIN_PRIV` (_Settings > Secrets_)
* Add the content of `franklin.pub` to a new _deploy key_ of the repository named `FRANKLIN_PUB` with write access.

**Git setup**

* Observe that the source is on the `dev` branch
* Deployed files are on the `master` branch (required by GitHub for a user website).

**GitHub action setup**

* [the github-action workflow](https://github.com/tlienart2/tlienart2.github.io/blob/dev/.github/workflows/deploy.yml)

