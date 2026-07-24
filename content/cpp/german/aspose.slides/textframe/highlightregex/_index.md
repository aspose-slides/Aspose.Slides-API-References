---
title: HighlightRegex()
second_title: Aspose.Slides für C++ API-Referenz
description: Markiert alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe.
type: docs
weight: 157
url: /de/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) Methode

Markiert alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Text des regulären Ausdrucks, um den zu markierenden Text zu erhalten. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe, um den Text zu markieren. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Optionen für die Hervorhebung. |

## Anmerkungen

Veraltet
:   Verwenden Sie stattdessen die Methode HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback). Die Methode wird nach der Veröffentlichung von Version 24.10 entfernt.


Das folgende Codebeispiel zeigt, wie man Text in einem [TextFrame](../) mit einem regulären Ausdruck hervorhebt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// Hervorhebung aller Wörter mit 10 oder mehr Zeichen
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) Methode

Markiert alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Der reguläre Ausdruck [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/), um die zu markierenden Zeichenketten zu erhalten. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe, um den Text zu markieren. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../ifindresultcallback/). |

## Anmerkungen



Das folgende Codebeispiel zeigt, wie man Text in einem [TextFrame](../) mit einem regulären Ausdruck hervorhebt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// Hervorhebung aller Wörter mit 10 oder mehr Zeichen
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Klasse [TextFrame](../)
* Klasse [Regex](../../../system.text.regularexpressions/regex/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)