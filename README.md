# DLP Tutorial

Start of a tutorial for accessing and working with DLP data.

Depends on the [scgenome package](https://scgenome.readthedocs.io/en/stable/).

## Environment

```
virtualenv venv
source venv_docs/bin/activate
pip install scgenome
pip install -e git+https://github.com/papaemmelab/isabl_cli.git@77554bfa64e1b468c78242f6ccbd37d99b0d9531#egg=isabl_cli
```

## Notebooks

See analyze_isabl_dlp.ipynb for an example of how to retrieve data from isabl and load into anndatas with scgenome.
