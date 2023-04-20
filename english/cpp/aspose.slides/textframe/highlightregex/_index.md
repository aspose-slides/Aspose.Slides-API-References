---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API Reference
description: Highlight all matches of regular expression in text frame text using specified color.
type: docs
weight: 118
url: /cpp/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


Highlight all matches of regular expression in text frame text using specified color.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Text of regular expression to get text to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Highlighting color. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Highlighting options. |
## Remarks



The following sample code shows how to Highlight Text using regular expression in a PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<Aspose::Slides::AutoShape>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

System::SharedPtr<TextHighlightingOptions> options = System::MakeObject<TextHighlightingOptions>();
// highlighting all words with 10 symbols or longer
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{5,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)