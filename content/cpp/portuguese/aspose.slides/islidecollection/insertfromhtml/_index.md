---
title: InsertFromHtml()
second_title: Referência da API Aspose.Slides para C++
description: Cria slides a partir de texto HTML e os insere na coleção na posição especificada.
type: docs
weight: 157
url: /pt/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlText | [System::String](../../../system/string/) | HTML a adicionar. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | [System::String](../../../system/string/) | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de Retorno

Slides adicionados.

## ISlideCollection::InsertFromHtml(int32_t, System::String) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlText | [System::String](../../../system/string/) | HTML a adicionar. |

### Valor de Retorno

Slides adicionados

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que será usado como fonte de um arquivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | [System::String](../../../system/string/) | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de Retorno

Slides adicionados.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objeto TextReader que será usado como fonte de um arquivo HTML. |

### Valor de Retorno

Slides adicionados

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | [System::String](../../../system/string/) | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de Retorno

Slides adicionados.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um objeto Stream que será usado como fonte de um arquivo HTML. |

### Valor de Retorno

Slides adicionados

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlText | [System::String](../../../system/string/) | HTML a adicionar. |
| useSlideWithIndexAsStart | **bool** | Este sinalizador determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

### Valor de Retorno

Slides adicionados

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlText | [System::String](../../../system/string/) | HTML a adicionar. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | [System::String](../../../system/string/) | Um URI do HTML especificado. Usado para resolver links relativos. |
| useSlideWithIndexAsStart | **bool** | Este sinalizador determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

### Valor de Retorno

Slides adicionados.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| useSlideWithIndexAsStart | **bool** | Este sinalizador determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

### Valor de Retorno

Slides adicionados

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Cria slides a partir do texto HTML e os insere na coleção na posição especificada.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Posição para inserir. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Um objeto de callback usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | [System::String](../../../system/string/) | Um URI do HTML especificado. Usado para resolver links relativos. |
| useSlideWithIndexAsStart | **bool** | Este sinalizador determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

### Valor de Retorno

Slides adicionados.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [ISlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)