---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
檢查用於修改的密碼是否正確，以判斷簡報是否受到寫入保護。

### 回傳值

True 如果簡報受到寫入保護且密碼正確。否則回傳 False。



```python
def check_write_protection(self, password):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| password | **str** | 要檢查的密碼。 |

### 備註

1. 在呼叫此方法之前，應先檢查 [`IPresentationInfo.is_write_protected`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/is_write_protected) 屬性。  
2. 當 password 為 None 或空值時，此方法會回傳 false。

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### 參見
* 類別 [`IPresentationInfo`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)