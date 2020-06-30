Enable debug statements in an IDE, Eclipse with pydev, or Pycharm, to print links to the line in the source code of the debug statement. 
    
```python

logger = logger.getLogger(__file__)
    
logger.debug("Test link to source")
```

Above code results in the output below, in IDE console, logger.py:3 linking to `logger.debug("Test link to source")`


`2020-06-30 12:15:53,708 | DEBUG | `[logger.py]()` | <module> | Test link to source            | `"[logger.py:3]()"`
