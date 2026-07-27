---
title: HighlightText()
second_title: Referência da API Aspose.Slides para C++
description: Realça todas as ocorrências do texto de amostra com a cor especificada.
type: docs
weight: 131
url: /pt/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) método

Realça todas as ocorrências do texto de amostra com a cor especificada.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto de amostra a realçar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para realçar o texto. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) método

Realça todas as ocorrências do texto de amostra com a cor especificada.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | O texto a realçar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para realçar o texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Opções de realce. |

## Observações

Obsoleto
:   Use o método HighlightText(string text, Color highlightColor, ITextSearchOptions options) em vez disso. O método será removido após o lançamento da versão 24.10.

O código de exemplo a seguir mostra como realçar texto em um [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// realçando todas as palavras 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// realçando todas as ocorrências separadas de 'the'
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) método

Realça todas as ocorrências do texto de amostra com a cor especificada.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | O texto a realçar. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para realçar o texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opções de pesquisa de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de retorno de chamada para receber resultados de pesquisa [IFindResultCallback](../../ifindresultcallback/). |

## Observações

O exemplo de código a seguir mostra como realçar texto em um [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// realçando todas as palavras 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// realçando todas as ocorrências separadas de 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [TextFrame](../)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)