---
title: check_write_protection method
second_title: Aspose.Slides 用於 Python 之 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
判斷簡報是否受到密碼保護以進行修改。

### 返回值
如果密碼有效則返回 True；否則返回 false。

```python
def check_write_protection(self, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | 用於檢查的密碼。 |

### 備註
1. 在呼叫此方法之前，應先檢查 [`IProtectionManager.is_write_protected`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager/is_write_protected) 屬性。  
2. 當密碼為 None 或空值時，此方法返回 false。

### 另請參閱
* class [`IProtectionManager`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager)
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)