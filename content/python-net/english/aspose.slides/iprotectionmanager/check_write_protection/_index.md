---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/iprotectionmanager/check_write_protection/
weight: 60
---


## check_write_protection {#string}
Determines whether a presentation is a password protected to modify.

### Returns

True if the password is valid; otherwise, false.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| password | string | The password for checking. |

### Remarks

1. You should check the [`IProtectionManager.is_write_protected`](/slides/python-net/aspose.slides/iprotectionmanager#is_write_protected) property before calling this method.
            2. When the password is null or empty, this method returns false.



