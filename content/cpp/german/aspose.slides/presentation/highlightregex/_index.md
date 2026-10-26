---
title: HighlightRegex()
second_title: Aspose.Slides für C++ API-Referenz
description: Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor.
type: docs
weight: 508
url: /de/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) Methode

Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Der reguläre Ausdruck [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) zum Abrufen von zu markierenden Zeichenfolgen. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Die Farbe zum Hervorheben des Textes. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../ifindresultcallback/). |

## Anmerkungen

Das folgende Codebeispiel zeigt, wie man Text in einer PowerPoint [Presentation](../) mithilfe eines regulären Ausdrucks hervorhebt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Regex](../../../system.text.regularexpressions/regex/)
* Klasse [Color](../../../system.drawing/color/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)