---
title: get_ParagraphFormat()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回此段落的格式化物件。唯讀 IParagraphFormat.
type: docs
weight: 14
url: /zh-hant/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() 方法

傳回此段落的格式化物件。唯讀 [IParagraphFormat](../../iparagraphformat/)。

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## 備註

格式化物件僅包含目前段落定義的格式參數，未套用繼承的資料。

若要取得包括繼承值在內的有效值，請使用 [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/) 方法。

## 另請參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IParagraphFormat](../../iparagraphformat/)
* 類別 [Paragraph](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)