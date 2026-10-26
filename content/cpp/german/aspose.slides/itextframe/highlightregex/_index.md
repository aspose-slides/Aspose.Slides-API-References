---
title: HighlightRegex()
second_title: Aspose.Slides für C++ API Referenz
description: Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor.
type: docs
weight: 131
url: /de/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) Methode

Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Der reguläre Ausdruck [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) zum Abrufen der zu hervorhebenden Zeichenfolgen. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe, mit der der Text hervorgehoben wird. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Callback-Objekt zum Empfangen der Suchergebnisse [IFindResultCallback](../../ifindresultcallback/). |

## Hinweise

Das folgende Codebeispiel zeigt, wie man Text in einem [TextFrame](../../textframe/) mithilfe eines regulären Ausdrucks hervorhebt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Alle Wörter mit 10 oder mehr Zeichen hervorheben
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Bllue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) Methode

Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Text des regulären Ausdrucks zum Abrufen des zu hervorgehobenen Textes. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe, mit der der Text hervorgehoben wird. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Hervorhebungsoptionen. |

Veraltet
:   Verwenden Sie stattdessen die Methode HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback). Die Methode wird nach der Veröffentlichung von Version 24.10 entfernt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Regex](../../../system.text.regularexpressions/regex/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [ITextFrame](../)
* Klasse [String](../../../system/string/)
* Klasse [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)