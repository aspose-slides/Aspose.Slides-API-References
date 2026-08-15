---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API 參考文件
description: 將正規表達式的所有匹配項以指定的顏色突顯。
type: docs
weight: 131
url: /zh-hant/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) 方法

將正規表達式的所有匹配項以指定的顏色突顯。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 用於取得要突顯之字串的正規表達式 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 突顯文字的顏色。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 用於接收搜尋結果 [IFindResultCallback](../../ifindresultcallback/) 的回呼物件。 |
## 備註



以下程式碼範例示範如何在 [TextFrame](../../textframe/) 中使用正規表達式突顯文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) 方法


將正規表達式的所有匹配項以指定的顏色突顯。

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | 用於取得要突顯文字的正規表達式文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 突顯文字的顏色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 突顯選項。 |

已棄用
:   請改用 HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) 方法。此方法將在 24.10 版發佈後移除。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Regex](../../../system.text.regularexpressions/regex/)
* 類別 [Color](../../../system.drawing/color/)
* 類別 [IFindResultCallback](../../ifindresultcallback/)
* 類別 [ITextFrame](../)
* 類別 [String](../../../system/string/)
* 類別 [ITextHighlightingOptions](../../itexthighlightingoptions/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)