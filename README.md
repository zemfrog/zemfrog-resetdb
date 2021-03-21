zemfrog-resetdb
===============

Command to reset the database for zemfrog.


Usage
-----

Install it first:

```sh
pip install zemfrog-resetdb
```

Plug it into the `COMMANDS` configuration in your zemfrog application:

```python
COMMANDS = [
    "zemfrog_resetdb"
]
```

Now you have installed the `resetdb` command in the application.

```sh
flask resetdb
```
