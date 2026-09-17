---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
确定演示文稿是否受密码保护以进行修改。

### Returns
如果密码有效则返回 True；否则返回 false。

```python
def check_write_protection(self, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | 用于检查的密码。 |

### Remarks
1. 在调用此方法之前，您应检查 [`IProtectionManager.is_write_protected`](/slides/python-net/zh/aspose.slides/iprotectionmanager/is_write_protected) 属性。  
2. 当 password 为 None 或为空时，此方法返回 false。

### See Also
* 类 [`IProtectionManager`](/slides/python-net/zh/aspose.slides/iprotectionmanager)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)