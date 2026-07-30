---
title: HighlightRegex()
second_title: Riferimento API di Aspose.Slides per C++
description: Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.
type: docs
weight: 131
url: /it/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metodo


Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L'espressione regolare [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) per ottenere le stringhe da evidenziare. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Il colore per evidenziare il testo. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../ifindresultcallback/). |
## Osservazioni



Il seguente esempio di codice mostra come evidenziare il testo in un [TextFrame](../../textframe/) usando un'espressione regolare. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metodo


Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Testo dell'espressione regolare per ottenere il testo da evidenziare. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Il colore per evidenziare il testo. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opzioni di evidenziazione. |

Obsoleto
:   Usa il metodo HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) invece. Il metodo sarà rimosso dopo il rilascio della versione 24.10.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [Color](../../../system.drawing/color/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [ITextFrame](../)
* Classe [String](../../../system/string/)
* Classe [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)