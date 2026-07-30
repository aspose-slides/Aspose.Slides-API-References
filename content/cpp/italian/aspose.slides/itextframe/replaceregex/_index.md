---
title: ReplaceRegex()
second_title: Riferimento API di Aspose.Slides per C++
description: Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata.
type: docs
weight: 157
url: /it/aspose.slides/itextframe/replaceregex/
---
## ITextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) metodo


Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L'espressione regolare [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) per ottenere le stringhe da sostituire. |
| newText | [System::String](../../../system/string/) | La stringa per sostituire tutte le occorrenze delle stringhe da sostituire. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../ifindresultcallback/). |
## Osservazioni



Il seguente esempio di codice mostra come sostituire il testo usando un'espressione regolare con la stringa specificata. 
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
* Classe [ITextFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)