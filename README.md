# Le Blog d'Omer


## Prerequisites

- Python ~3.10

- Poetry


## Environment variable

To communicate with the Disqus app that that handles the comments for this blog, the `DISQUS_SHORTNAME` env variable needs to be set. So, before running the `serve`, `build` or `gh-deploy` commands, set this variable with:

```bash
export DISQUS_SHORTNAME="<disqus-shortname>"
```

