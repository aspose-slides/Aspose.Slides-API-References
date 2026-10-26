---
title: set_InterruptionToken()
second_title: Aspose.Slides for C++ API 參考文件
description: 用於監測中斷請求的令牌。
type: docs
weight: 248
url: /zh-hant/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) 方法

用於監測中斷請求的令牌。

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## 備註

此令牌管理整個 [IPresentation](../../ipresentation/) 實例的生命週期。任何長時間執行的操作，例如簡報載入或儲存，將透過呼叫 [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) 方法（屬於 [IInterruptionTokenSource](../../iinterruptiontokensource/)）而中斷。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IInterruptionToken](../../iinterruptiontoken/)
* 類別 [ILoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)