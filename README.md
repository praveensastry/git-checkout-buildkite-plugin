# git-checkout-buildkite-plugin
Overwrites the git checkout behaviour for a job

### requirements

This plugin expects the below env vars

```
GIT_REPO_URL=<repo_to_be_built>
GIT_REF_SPEC=<SHA_for_the_commit>
```