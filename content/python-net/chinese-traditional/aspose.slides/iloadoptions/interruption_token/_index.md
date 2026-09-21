---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token 屬性
用於監視中斷請求的令牌。

此令牌管理整個 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 實例的生命週期。任何長時間執行的操作，例如簡報的載入或儲存，將透過呼叫 [`IInterruptionTokenSource.interrupt`](/slides/python-net/zh-hant/aspose.slides/iinterruptiontokensource/interrupt) 方法來中斷 [`IInterruptionTokenSource`](/slides/python-net/zh-hant/aspose.slides/iinterruptiontokensource)。

### 定義:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### 參見
* 類別 [`IInterruptionTokenSource`](/slides/python-net/zh-hant/aspose.slides/iinterruptiontokensource)
* 類別 [`ILoadOptions`](/slides/python-net/zh-hant/aspose.slides/iloadoptions)
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)