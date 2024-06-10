---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API Reference
description: Highlights all matches of the regular expression with the specified color.
type: docs
weight: 92
url: /aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method


Highlights all matches of the regular expression with the specified color.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | The regular expression [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) to get strings to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | The color to highlight the text. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | The callback object for receiving search results [IFindResultCallback](../../ifindresultcallback/). |
## Remarks



The following code sample shows how to highlight text in a [TextFrame](../../textframe/) using a regular expression. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


Highlights all matches of the regular expression with the specified color.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Text of regular expression to get text to highlight. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | The color to highlight the text. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Highlighting options. |

Deprecated
:   Use HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) method instead. The method will be removed after release of version 24.10.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [Color](../../../system.drawing/color/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [ITextFrame](../)
* Class [String](../../../system/string/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)