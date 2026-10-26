---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
檢查用於修改的密碼在受寫保護的簡報中是否正確。

### 返回值

如果簡報受寫保護且密碼正確，則回傳 True；否則回傳 False。



```python
def check_write_protection(self, password):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| password | **str** | 要檢查的密碼。 |

### 備註

1. 在呼叫此方法之前，您應該檢查 [`PresentationInfo.is_write_protected`](/slides/python-net/zh-hant/aspose.slides/presentationinfo/is_write_protected) 屬性。  
2. 當 password 為 None 或為空時，此方法回傳 false。

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### 另請參閱
* 類別 [`PresentationInfo`](/slides/python-net/zh-hant/aspose.slides/presentationinfo)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)