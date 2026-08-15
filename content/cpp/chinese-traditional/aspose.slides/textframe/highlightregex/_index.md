---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API 參考
description: 以指定的顏色突顯正則表達式的所有匹配項目。
type: docs
weight: 157
url: /zh-hant/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


以指定的顏色突顯正則表達式的所有匹配項目。

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | 正則表達式的文字，用於取得要突顯的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於突顯文字的顏色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 突顯選項。 |
## 備註


已棄用
:   請改用 HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) 方法。此方法將在 24.10 版發佈後移除。


以下程式碼範例示範如何使用正則表達式在 [TextFrame](../) 中突顯文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// 突顯所有長度為 10 個或以上字元的單字
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method


以指定的顏色突顯正則表達式的所有匹配項目。

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | 正則表達式 [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) 以取得要突顯的字串。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於突顯文字的顏色。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 接收搜尋結果 [IFindResultCallback](../../ifindresultcallback/) 的回呼物件。 |
## 備註



以下程式碼範例示範如何使用正則表達式在 [TextFrame](../) 中突顯文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// 突顯所有長度為 10 個或以上字元的單字
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [TextFrame](../)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)