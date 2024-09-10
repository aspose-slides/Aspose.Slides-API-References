---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---


## check_write_protection {#str}
Checks whether a password to modify is correct for a write protected presentation.

### Returns

True if the presentation is write protected and the password is correct. False otherwise.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | The password to check. |

### Remarks

1. You should check the [`IPresentationInfo.is_write_protected`](/slides/python-net/aspose.slides/ipresentationinfo/is_write_protected) property before calling this method.
            2. When password is None or empty, this method returns false.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### See Also
* class [`IPresentationInfo`](/slides/python-net/aspose.slides/ipresentationinfo)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

