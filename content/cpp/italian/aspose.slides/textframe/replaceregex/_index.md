---
title: ReplaceRegex()
second_title: Riferimento API Aspose.Slides per C++
description: Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata.
type: docs
weight: 183
url: /it/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metodo

Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L'espressione regolare [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) per ottenere le stringhe da sostituire. |
| newText | [System::String](../../../system/string/) | La stringa con cui sostituire tutte le occorrenze delle stringhe da sostituire. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Oggetto di callback per salvare il risultato dell'operazione di sostituzione [IFindResultCallback](../../ifindresultcallback/). |

## Osservazioni

Il seguente codice di esempio mostra come sostituire il testo usando un'espressione regolare con la stringa specificata. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [String](../../../system/string/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [TextFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)