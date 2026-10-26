---
title: get_InterruptionToken()
second_title: Aspose.Slides for C++ API 參考
description: 用於監測中斷請求的代幣。
type: docs
weight: 235
url: /zh-hant/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() 方法

用於監測中斷請求的代幣。

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```
## 備註

此代幣管理整個 [IPresentation](../../ipresentation/) 實例的生命週期。任何長時間執行的操作，例如載入或儲存簡報，皆會透過呼叫 [InterruptionTokenSource](../../interruptiontokensource/) 的 [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) 方法而被中斷。 
## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IInterruptionToken](../../iinterruptiontoken/)
* 類別 [LoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)