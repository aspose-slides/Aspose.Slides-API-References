---
title: HighlightText()
second_title: Aspose.Slides for C++ API Reference
description: Highlights all matches of the sample text with the specified color.
type: docs
weight: 79
url: /aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) method


Highlights all matches of the sample text with the specified color.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | The text to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | The color to highlight the text. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


Highlights all matches of the sample text with the specified color.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | The text to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | The color to highlight the text. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Highlighting options. |

Deprecated
:   Use HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) method instead. The method will be removed after release of version 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


Highlights all matches of the sample text with the specified color.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | The text to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | The color to highlight the text. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Text search options [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | The callback object for receiving search results [IFindResultCallback](../../ifindresultcallback/). |
## Remarks



The following code sample shows how to highlight text in a [TextFrame](../../textframe/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextFrame](../)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)