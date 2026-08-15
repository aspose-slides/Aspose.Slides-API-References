---
title: set_InterruptionToken()
second_title: Aspose.Slides for C++ API 參考
description: 用於監視中斷請求的令牌。
type: docs
weight: 248
url: /zh-hant/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) 方法

用於監視中斷請求的令牌。

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## 備註

此令牌管理整個 [IPresentation](../../ipresentation/) 實例的生命週期。任何長時間執行的操作，例如載入或儲存簡報，都會透過呼叫 [InterruptionTokenSource](../../interruptiontokensource/) 的 [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) 方法而被中斷。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IInterruptionToken](../../iinterruptiontoken/)
* 類別 [LoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)