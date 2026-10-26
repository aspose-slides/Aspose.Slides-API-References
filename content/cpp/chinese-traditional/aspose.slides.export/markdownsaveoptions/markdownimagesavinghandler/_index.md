---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides for C++ API 參考
description: 在 Markdown 匯出期間，對每個非 SVG 圖像（點陣圖或圖元檔）呼叫此處理程式。返回 true 以使用指定的連結，或 false 以套用預設的儲存邏輯。
type: docs
weight: 300
url: /zh-hant/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


在 Markdown 匯出期間，對每個非 SVG 圖像（點陣圖或圖元檔）呼叫此處理程式。

 返回 **true** 以使用指定的 *連結* ，

 或 **false** 以套用預設的儲存邏輯。

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## 另見

* 類別 [MarkdownSaveOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)