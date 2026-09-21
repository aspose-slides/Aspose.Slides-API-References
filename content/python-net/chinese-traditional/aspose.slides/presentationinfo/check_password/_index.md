---
title: check_password method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
檢查對於受開放密碼保護的簡報，密碼是否正確。

### 回傳值

若簡報受開放密碼保護且密碼正確則回傳 true，否則回傳 false。

```python
def check_password(self, password):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| password | **str** | 要檢查的密碼。 |

### 備註

當密碼為 None 或為空字串時，此方法回傳 false。

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |

### 另見
* 類別 [`PresentationInfo`](/slides/python-net/zh-hant/aspose.slides/presentationinfo)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)