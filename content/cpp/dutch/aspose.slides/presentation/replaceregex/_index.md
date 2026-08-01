---
title: ReplaceRegex()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks.
type: docs
weight: 534
url: /nl/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) methode

Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | De reguliere expressie [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) om de te vervangen tekenreeksen te verkrijgen. |
| newText | [System::String](../../../system/string/) | De tekenreeks om alle voorkomens van de te vervangen tekenreeksen te vervangen. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Het callback object voor het ontvangen van zoekresultaten [IFindResultCallback](../../ifindresultcallback/). |

## Opmerkingen

Het volgende codevoorbeeld toont hoe tekst te vervangen met behulp van een reguliere expressie en de opgegeven tekenreeks. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)