---
title: HighlightText()
second_title: Aspose.Slides for C++ API 參考
description: 將樣本文本的所有匹配項以指定顏色凸顯。
type: docs
weight: 131
url: /zh-hant/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) method


將樣本文本的所有匹配項以指定顏色凸顯。

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 用於凸顯的文字樣本。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於凸顯文字的顏色。 |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


將樣本文本的所有匹配項以指定顏色凸顯。

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要凸顯的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於凸顯文字的顏色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | 凸顯選項。 |
## 備註


已棄用
:   請改用 HighlightText(string text, Color highlightColor, ITextSearchOptions options) 方法。此方法將在 24.10 版發布後被移除。

以下範例程式碼示範如何在 [TextFrame](../) 中使用 HighlightText。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


將樣本文本的所有匹配項以指定顏色凸顯。

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 要凸顯的文字。 |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | 用於凸顯文字的顏色。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | 文字搜尋選項 [ITextSearchOptions](../../itextsearchoptions/)。 |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | 接收搜尋結果的回呼物件 [IFindResultCallback](../../ifindresultcallback/)。 |
## 備註



以下程式碼範例示範如何在 [TextFrame](../) 中凸顯文字。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// 凸顯所有單詞 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// 凸顯所有單獨出現的 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [TextFrame](../)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)