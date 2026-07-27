---
title: HighlightText()
second_title: Referência da API Aspose.Slides para C++
description: Realça todas as correspondências do texto de exemplo com a cor especificada.
type: docs
weight: 456
url: /pt/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) método


Realça todas as correspondências do texto de exemplo com a cor especificada.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | O texto a ser realçado. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para realçar o texto. |
## Observações



O exemplo de código a seguir mostra como realçar texto em uma apresentação do PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// highlighting all separate 'the' occurrences
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) método


Realça todas as correspondências do texto de exemplo com a cor especificada.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | O texto a ser realçado. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A cor para realçar o texto. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opções de busca de texto [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | O objeto de retorno de chamada para receber os resultados da busca [IFindResultCallback](../../ifindresultcallback/). |
## Observações



O exemplo de código a seguir mostra como realçar texto em uma apresentação do PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// realçando todas as ocorrências separadas de 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Veja Também

* Definição de Tipo [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Color](../../../system.drawing/color/)
* Classe [IPresentation](../)
* Classe [ITextSearchOptions](../../itextsearchoptions/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)