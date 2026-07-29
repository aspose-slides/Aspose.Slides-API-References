---
title: HighlightRegex()
second_title: Aspose.Slides för C++ API-referens
description: Markerar alla träffar av det reguljära uttrycket med den angivna färgen.
type: docs
weight: 157
url: /sv/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metod

Markerar alla träffar av reguljära uttrycket med den angivna färgen.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Texten för reguljärt uttryck för att hämta texten som ska markeras. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen för att markera texten. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Markeringsalternativ. |

## Anmärkningar

Föråldrad
:   Använd HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) metod istället. Metoden kommer att tas bort efter utgåvan av version 24.10.

Följande kodexempel visar hur man markerar text i en [TextFrame](../) med ett reguljärt uttryck. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// markerar alla ord med 10 eller fler tecken
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metod

Markerar alla träffar av reguljära uttrycket med den angivna färgen.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Det reguljära uttrycket [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) för att hämta strängar att markera. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Färgen för att markera texten. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Återanropsobjektet för att ta emot sökresultat [IFindResultCallback](../../ifindresultcallback/). |

## Anmärkningar



Följande kodexempel visar hur man markerar text i en [TextFrame](../) med ett reguljärt uttryck. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// markerar alla ord med 10 eller fler tecken
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Color](../../../system.drawing/color/)
* Klass [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Klass [TextFrame](../)
* Klass [Regex](../../../system.text.regularexpressions/regex/)
* Klass [IFindResultCallback](../../ifindresultcallback/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)