---
title: HighlightRegex()
second_title: Riferimento API Aspose.Slides per C++
description: Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.
type: docs
weight: 157
url: /it/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metodo


Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Testo dell'espressione regolare per ottenere il testo da evidenziare. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Il colore con cui evidenziare il testo. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opzioni di evidenziazione. |
## Note


Deprecata
:   Use HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) method instead. The method will be removed after release of version 24.10.


Il seguente esempio di codice mostra come evidenziare il testo in un [TextFrame](../) usando un'espressione regolare. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// evidenziando tutte le parole con 10 o più caratteri
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metodo


Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L'espressione regolare [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) per ottenere le stringhe da evidenziare. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Il colore con cui evidenziare il testo. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../ifindresultcallback/). |
## Note



Il seguente esempio di codice mostra come evidenziare il testo in un [TextFrame](../) usando un'espressione regolare. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// evidenziando tutte le parole con 10 o più caratteri
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Color](../../../system.drawing/color/)
* Classe [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Classe [TextFrame](../)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)