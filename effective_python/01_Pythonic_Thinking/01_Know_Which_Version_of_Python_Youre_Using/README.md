## Item 1: Know Which Version of Python You're Using

### Code

```
[wyi@wkpc ~]$ python3 --version
Python 3.5.2
[wyi@wkpc ~]$ python3
Python 3.5.2 (default, Sep 14 2016, 11:28:32)
[GCC 6.2.1 20160901 (Red Hat 6.2.1-1)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import sys
>>> print(sys.version_info)
sys.version_info(major=3, minor=5, micro=2, releaselevel='final', serial=0)
>>> print(sys.version)
3.5.2 (default, Sep 14 2016, 11:28:32)
[GCC 6.2.1 20160901 (Red Hat 6.2.1-1)]
>>>
```

### Things to Remember

- Python 2 & Python 3.
- Runtime
    - CPython
    - Jython
    - IronPython
    - PyPy
    - Others
- Be sure that the command-line for runing Python on your system is the version you expect it to be.
- Prefer Python 3
