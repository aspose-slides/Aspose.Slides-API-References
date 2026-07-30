---
title: HighlightRegex()
second_title: Riferimento API Aspose.Slides per C++
description: Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.
type: docs
weight: 508
url: /it/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metodo

Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L'espressione regolare [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) per ottenere le stringhe da evidenziare. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Il colore per evidenziare il testo. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../ifindresultcallback/). |
## Osservazioni

Il seguente esempio di codice mostra come evidenziare il testo in un PowerPoint [Presentation](../) utilizzando un'espressione regolare.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// evidenzia tutte le parole con 10 o più caratteri
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [Color](../../../system.drawing/color/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)