---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
判斷簡報是否受密碼保護以供修改。

### 返回值

True if the password is valid; otherwise, false.



```python
def check_write_protection(self, password):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| password | **str** | 用於檢查的密碼。 |

### 備註

1. 在呼叫此方法之前，您應該檢查 [`ProtectionManager.is_write_protected`](/slides/python-net/zh-hant/aspose.slides/protectionmanager/is_write_protected) 屬性。
            2. 當密碼為 None 或空值時，此方法返回 false。



### 另見
* 類別 [`ProtectionManager`](/slides/python-net/zh-hant/aspose.slides/protectionmanager)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)