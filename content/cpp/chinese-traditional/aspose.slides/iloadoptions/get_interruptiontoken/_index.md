---
title: get_InterruptionToken()
second_title: Aspose.Slides for C++ API 參考文件
description: 用於監視中斷請求的標記。
type: docs
weight: 235
url: /zh-hant/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() 方法

用於監視中斷請求的標記。

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## 備註

此標記管理整個 [IPresentation](../../ipresentation/) 實例的生命週期。任何長時間執行的操作，例如簡報載入或保存，將透過呼叫 [IInterruptionTokenSource](../../iinterruptiontokensource/) 的 [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) 方法來中斷。

## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IInterruptionToken](../../iinterruptiontoken/)
* 類別 [ILoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)