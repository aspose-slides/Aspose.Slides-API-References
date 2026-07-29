---
title: HighlightRegex()
second_title: Aspose.Slides för C++ API-referens
description: Markerar alla träffar av det reguljära uttrycket med den angivna färgen.
type: docs
weight: 131
url: /sv/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

Markerar alla träffar av reguljära uttrycket med den angivna färgen.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Reguljärt uttryck [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) för att hämta strängar att markera. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen för att markera texten. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Återuppringningsobjektet för att ta emot sökresultat [IFindResultCallback](../../ifindresultcallback/). |

## Remarks

Följande kodexempel visar hur man markerar text i en [TextFrame](../../textframe/) med ett reguljärt uttryck. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// markerar alla ord med 10 eller fler tecken
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

Markerar alla träffar av reguljära uttrycket med den angivna färgen.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Text för reguljärt uttryck för att hämta text att markera. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen för att markera texten. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Alternativ för markering. |

Inaktiverad
:   Använd HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback)-metoden istället. Metoden kommer att tas bort efter version 24.10 släppts.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Regex](../../../system.text.regularexpressions/regex/)
* Klass [Color](../../../system.drawing/color/)
* Klass [IFindResultCallback](../../ifindresultcallback/)
* Klass [ITextFrame](../)
* Klass [String](../../../system/string/)
* Klass [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)