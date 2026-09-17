---
title: check_write_protection method
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
检查用于修改的密码是否正确，以保护写入受保护的演示文稿。

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

1. 在调用此方法之前，您应该检查 [`PresentationInfo.is_write_protected`](/slides/python-net/zh/aspose.slides/presentationinfo/is_write_protected) 属性。
2. 当 password 为 None 或空时，此方法返回 false。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### 另请参阅
* 类 [`PresentationInfo`](/slides/python-net/zh/aspose.slides/presentationinfo)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)