---
title: HighlightText()
second_title: Referência da API Aspose.Slides para C++
description: Realça todas as ocorrências do texto de exemplo com a cor especificada.
type: docs
weight: 495
url: /pt/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) método

Realça todas as ocorrências do texto de exemplo com a cor especificada.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | O texto a ser realçado. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para realçar o texto. |
## Observações

O exemplo de código a seguir demonstra como realçar texto em uma apresentação do PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// realçando todas as ocorrências separadas de 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) método

Realça todas as ocorrências do texto de exemplo com a cor especificada.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | O texto a ser realçado. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para realçar o texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opções de pesquisa de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de retorno de chamada para receber resultados da pesquisa [IFindResultCallback](../../ifindresultcallback/). |
## Observações

O exemplo de código a seguir demonstra como realçar texto em uma apresentação do PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// realçando todas as ocorrências separadas de 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [Presentation](../)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)