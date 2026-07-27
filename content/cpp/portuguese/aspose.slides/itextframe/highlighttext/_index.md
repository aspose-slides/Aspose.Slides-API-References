---
title: HighlightText()
second_title: Referência da API Aspose.Slides para C++
description: Destaca todas as ocorrências do texto de exemplo com a cor especificada.
type: docs
weight: 105
url: /pt/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) método


Destaca todas as ocorrências do texto de exemplo com a cor especificada.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | O texto a ser destacado. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para destacar o texto. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) método


Destaca todas as ocorrências do texto de exemplo com a cor especificada.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | O texto a ser destacado. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para destacar o texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opções de destaque. |

Obsoleta
:   Use HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) método instead. O método será removido após o lançamento da versão 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) método


Destaca todas as ocorrências do texto de exemplo com a cor especificada.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | O texto a ser destacado. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para destacar o texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opções de pesquisa de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de retorno de chamada para receber resultados da pesquisa [IFindResultCallback](../../ifindresultcallback/). |

## Observações



O exemplo de código a seguir mostra como destacar texto em um [TextFrame](../../textframe/). 
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

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Color](../../../system.drawing/color/)
* Classe [ITextFrame](../)
* Classe [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Classe [ITextSearchOptions](../../itextsearchoptions/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)