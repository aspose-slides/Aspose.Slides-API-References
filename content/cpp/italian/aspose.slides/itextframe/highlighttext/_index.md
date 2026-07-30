---
title: HighlightText()
second_title: Riferimento API di Aspose.Slides per C++
description: Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato.
type: docs
weight: 105
url: /it/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) metodo


Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Il testo da evidenziare. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Il colore per evidenziare il testo. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metodo


Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Il testo da evidenziare. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Il colore per evidenziare il testo. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opzioni di evidenziazione. |

Obsoleto
:   Utilizzare il metodo HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) invece. Il metodo sarà rimosso dopo il rilascio della versione 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metodo


Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Il testo da evidenziare. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Il colore per evidenziare il testo. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opzioni di ricerca del testo [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../ifindresultcallback/). |
## Osservazioni



Il seguente esempio di codice mostra come evidenziare il testo in un [TextFrame](../../textframe/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Color](../../../system.drawing/color/)
* Classe [ITextFrame](../)
* Classe [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Classe [ITextSearchOptions](../../itextsearchoptions/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)