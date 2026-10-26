---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token 屬性
用於監控中斷請求的代幣。
            
            此代幣管理整個 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 實例的生命週期。
            或儲存簡報，將透過呼叫 [`InterruptionTokenSource.interrupt`](/slides/python-net/zh-hant/aspose.slides/interruptiontokensource/interrupt) 方法而被中斷 
            [`InterruptionTokenSource`](/slides/python-net/zh-hant/aspose.slides/interruptiontokensource)。

### 定義:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### 另見
* 類別 [`InterruptionTokenSource`](/slides/python-net/zh-hant/aspose.slides/interruptiontokensource)
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 類別 [`LoadOptions`](/slides/python-net/zh-hant/aspose.slides/loadoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)