# What is \_\_name\_\_ in Python?
`__name__` is a path where the script, module or package is.
And this repository shows you how `__name__` works.
```
$ git clone https://github.com/niconico25/__name__
$ python3 script.py 
__file__: script.py
__name__: __main__
__file__: /Users/user/__name__/package0/__init__.py
__name__: package0
__file__: /Users/user/__name__/package0/module1.py
__name__: package0.module1
__file__: /Users/user/__name__/package0/package1/__init__.py
__name__: package0.package1
__file__: /Users/user/__name__/package0/package1/module2.py
__name__: package0.package1.module2
$ tree
```
```
$ tree
.
├── script.py
└── package0
    ├── __init__.py
    ├── module1.py
    └── package1
        ├── __init__.py
        └── module2.py

2 directories, 5 files
$ 
```



> [\_\_name\_\_](https://docs.python.org/3/reference/import.html?highlight=__name__#__name__)<br>
> The `__name__` attribute must be set to the fully-qualified name of the module.
> This name is used to uniquely identify the module in the import system.


