---
title: ExportToHtml()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的段落轉換為 HTML，並以 String 物件返回。
type: docs
weight: 170
url: /zh-hant/aspose.slides/paragraphcollection/exporttohtml/
---
## ParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) 方法

將指定的段落轉換為 HTML，並以 String 物件返回。

```cpp
System::String Aspose::Slides::ParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | 第一段落索引 **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) 計數 **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | 轉換選項 [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### 返回值

產生的 HTML。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* 類別 [ParagraphCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)