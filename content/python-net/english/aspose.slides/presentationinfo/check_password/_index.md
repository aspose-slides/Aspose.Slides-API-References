---
title: check_password method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentationinfo/check_password/
weight: 10
---


## check_password {#str}
Checks whether a password is correct for a presentation protected with open password.

### Returns

True if the presentation is protected with open password and the password is correct and false otherwise.



```python
def check_password(self, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | The password to check. |

### Remarks

When the password is None or empty, this method returns false.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### See Also
* class [`PresentationInfo`](/slides/python-net/aspose.slides/presentationinfo)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

