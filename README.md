### doit
---
https://github.com/pydoit/doit

http://pydoit.org/

```py
// tests/test_loader.py

class TEstFlatGenerator(object):
  def test_nested(self):
    def myg(items):
      for x in items:
        yield x
    flat = flat_generator(myg([1, myg([2, myg([3, myg([4, myg([5])])])])]))
    assert [1,2,3,4,5] == [f[0] for f in flat]

class TestGetModuel(object):
  def testAbsolutePath(self, restore_cwd):
    fileName = os.path.join(os.path.dirname(__file__),"loader_sample.py")
    dodo_module = get_module(fileName)
    assert hasattr(dodo_module, 'task_xxx1')
    
  def testRelativePath(self, restore_cwd):
  
  def testWrongFileName(self):
  
  def testInParentDir(self, restore_cwd):
  
```

```
```

```
```


