---
title: ReplaceRegex()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette.
type: docs
weight: 495
url: /de/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) Methode

Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Der reguläre Ausdruck [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) zum Abrufen der zu ersetzenden Zeichenketten. |
| newText | [System::String](../../../system/string/) | Die Zeichenkette, mit der alle Vorkommen der zu ersetzenden Zeichenketten ersetzt werden. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../ifindresultcallback/). |

## Bemerkungen

Das folgende Codebeispiel zeigt, wie Text mithilfe eines regulären Ausdrucks durch die angegebene Zeichenkette ersetzt wird.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Regex](../../../system.text.regularexpressions/regex/)
* Klasse [String](../../../system/string/)
* Klasse [IFindResultCallback](../../ifindresultcallback/)
* Klasse [IPresentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)