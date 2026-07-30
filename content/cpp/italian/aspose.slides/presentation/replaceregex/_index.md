---
title: ReplaceRegex()
second_title: Riferimento API di Aspose.Slides per C++
description: Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata.
type: docs
weight: 534
url: /it/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metodo


Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L'espressione regolare [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) per ottenere le stringhe da sostituire. |
| newText | [System::String](../../../system/string/) | La stringa per sostituire tutte le occorrenze delle stringhe da sostituire. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../ifindresultcallback/). |
## Note



Il seguente esempio di codice mostra come sostituire il testo utilizzando un'espressione regolare con la stringa specificata. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)