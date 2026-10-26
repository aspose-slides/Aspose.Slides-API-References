---
title: check_password method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ipresentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
检查密码是否正确，用于受开放密码保护的演示文稿。

### 返回

如果演示文稿受开放密码保护且密码正确，则返回 true；否则返回 false。

```python
def check_password(self, password):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| password | **str** | 要检查的密码。 |

### 备注

当密码为 None 或为空时，此方法返回 false。

### 另见
* 类 [`IPresentationInfo`](/slides/python-net/zh/aspose.slides/ipresentationinfo)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)