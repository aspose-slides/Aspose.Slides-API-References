---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
确定演示文稿是否受到密码保护以进行修改。

### 返回

如果密码有效则返回 True；否则返回 false.



```python
def check_write_protection(self, password):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| password | **str** | 用于检查的密码。 |

### 备注

1. 在调用此方法之前，您应该检查 [`ProtectionManager.is_write_protected`](/slides/python-net/zh/aspose.slides/protectionmanager/is_write_protected) 属性。
            2. 当密码为 None 或为空时，此方法返回 false.



### 另见
* 类 [`ProtectionManager`](/slides/python-net/zh/aspose.slides/protectionmanager)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)