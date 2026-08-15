---
title: MarkdownSvgImageSavingHandler
second_title: Aspose.Slides C++ API 參考
description: 在 Markdown 匯出期間對每個 SVG 圖像呼叫此處理常式。傳回 true 以使用指定的連結，或 false 以套用預設的儲存邏輯。
type: docs
weight: 313
url: /zh-hant/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef


在 Markdown 匯出期間對每個 SVG 圖像呼叫此處理常式。 

 傳回 **true** 以使用指定的 *連結* ， 

 或 **false** 以套用預設的儲存邏輯。

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```


## 參見

* 類別 [MarkdownSaveOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)