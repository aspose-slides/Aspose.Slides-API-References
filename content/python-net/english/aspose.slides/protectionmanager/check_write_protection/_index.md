---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/protectionmanager/check_write_protection/
weight: 10
---


## check_write_protection {#str}
Determines whether a presentation is a password protected to modify.

### Returns

True if the password is valid; otherwise, false.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | The password for checking. |

### Remarks

1. You should check the [`ProtectionManager.is_write_protected`](/slides/python-net/aspose.slides/protectionmanager/is_write_protected) property before calling this method.
            2. When the password is None or empty, this method returns false.



### See Also
* class [`ProtectionManager`](/slides/python-net/aspose.slides/protectionmanager)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

