---
title: ReplaceRegex()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette.
type: docs
weight: 534
url: /de/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method

Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Der reguläre Ausdruck [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) zum Ermitteln der zu ersetzenden Zeichenketten. |
| newText | [System::String](../../../system/string/) | Die Zeichenkette, die alle Vorkommen der zu ersetzenden Zeichenketten ersetzt. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Das Callback-Objekt zum Empfangen der Suchergebnisse [IFindResultCallback](../../ifindresultcallback/). |

## Anmerkungen


Das folgende Codebeispiel zeigt, wie man Text mithilfe eines regulären Ausdrucks durch die angegebene Zeichenkette ersetzt.
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
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)