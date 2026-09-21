---
title: InterruptionToken class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/interruptiontoken/
---
## InterruptionToken 類別

此類別表示用於向長時間執行的任務發送是否請求中斷訊號的代幣。

InterruptionToken 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`none`](/slides/python-net/zh-hant/aspose.slides/interruptiontoken/none/) | 表示一個空的中斷代幣。<br/>            使用此代幣時，長時間執行的操作將永不透過 [`InterruptionTokenSource.interrupt`](/slides/python-net/zh-hant/aspose.slides/interruptiontokensource/interrupt) 被中斷。 |
| [`is_interruption_requested`](/slides/python-net/zh-hant/aspose.slides/interruptiontoken/is_interruption_requested/) | 如果請求了中斷，回傳 **bool**.true。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/zh-hant/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | 拋出 OperationCanceledException 如果<br/>            請求了中斷。 |

### 參見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)