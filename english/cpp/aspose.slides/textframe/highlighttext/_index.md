---
title: HighlightText()
second_title: Aspose.Slides for C++ API Reference
description: Highlight all matches of sample in text frame text using specified color.
type: docs
weight: 105
url: /cpp/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText([System::String](../../../system/string/), [System::Drawing::Color](../../../system.drawing/color/)) method


Highlight all matches of sample in text frame text using specified color.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text sample to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Highlighting color. |

## See Also

* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## TextFrame::HighlightText([System::String](../../../system/string/), [System::Drawing::Color](../../../system.drawing/color/), [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\>) method


Highlight all matches of sample in text frame text using specified color.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text sample to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Highlighting color. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Highlighting options. |
## Remarks



The following sample code shows how to Highlight Text in a PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<Aspose::Slides::AutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());
// highlighting all separate 'the' occurrences
System::SharedPtr<TextHighlightingOptions> textHighlightingOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightingOptions->set_WholeWordsOnly(true);
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightingOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## See Also

* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
