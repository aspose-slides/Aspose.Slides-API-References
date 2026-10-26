---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
检查用于修改的密码是否正确，以确定演示文稿是否受写保护。

### 返回值

如果演示文稿受到写保护且密码正确，则返回 True；否则返回 False。

```python
def check_write_protection(self, password):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| password | **str** | 要检查的密码。 |

### 备注

1. 调用此方法前应检查 [`IPresentationInfo.is_write_protected`](/slides/python-net/zh/aspose.slides/ipresentationinfo/is_write_protected) 属性。
2. 当 password 为 None 或为空时，此方法返回 false。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### 另见
* class [`IPresentationInfo`](/slides/python-net/zh/aspose.slides/ipresentationinfo)
* module [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)