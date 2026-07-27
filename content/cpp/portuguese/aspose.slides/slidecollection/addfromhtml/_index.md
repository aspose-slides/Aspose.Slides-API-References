---
title: AddFromHtml()
second_title: Referência da API Aspose.Slides para C++
description: Cria slides a partir de texto HTML e os adiciona ao final da coleção.
type: docs
weight: 196
url: /pt/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html a ser adicionado. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo todos os objetos externos serão ignorados. |
| uri | [System::String](../../../system/string/) | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de retorno

Slides adicionados.

## SlideCollection::AddFromHtml(System::String) método

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html a ser adicionado. |

### Valor de retorno

Slides adicionados

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que será usado como origem de um arquivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo todos os objetos externos serão ignorados. |
| uri | [System::String](../../../system/string/) | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de retorno

Slides adicionados.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) método

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que será usado como origem de um arquivo HTML. |

### Valor de retorno

Slides adicionados

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) método

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um objeto Stream que será usado como origem de um arquivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo todos os objetos externos serão ignorados. |
| uri | [System::String](../../../system/string/) | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de retorno

Slides adicionados.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) método

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um objeto Stream que será usado como origem de um arquivo HTML. |

### Valor de retorno

Slides adicionados

## Observações

```cpp
// Crie uma instância da classe Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Chame o método AddFromHtml e passe o arquivo HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Use o método Save para salvar o arquivo como um documento PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [String](../../../system/string/)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Classe [SlideCollection](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)