=== Usage ===
```bash
oc process -f pipeline-template.yaml -v 'GIT_URL=<git_url>,GIT_REF=<git_ref>' | oc apply -f -
```
