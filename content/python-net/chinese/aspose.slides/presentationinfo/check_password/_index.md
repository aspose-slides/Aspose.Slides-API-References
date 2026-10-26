---
title: check_password method
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
检查对于使用打开密码保护的演示文稿，提供的 password 是否正确。

### Returns

True if the presentation is protected with open password and the password is correct and false otherwise.

```python
def check_password(self, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | 要检查的 password. |

### Remarks

当 password 为 None 或为空时，此方法返回 false.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |

### See Also
* class [`PresentationInfo`](/slides/python-net/zh/aspose.slides/presentationinfo)
* module [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)