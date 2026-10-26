---
title: InsertFromHtml
second_title: Referência da API Aspose.Slides para .NET
description: Cria slides a partir de texto HTML e os insere na coleção na posição especificada.
type: docs
weight: 140
url: /pt/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlText | String | HTML a ser adicionado. |
| resolver | IExternalResourceResolver | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | String | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de Retorno

Slides adicionados.

### Veja Também

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlText | String | HTML a ser adicionado. |
| resolver | IExternalResourceResolver | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | String | Um URI do HTML especificado. Usado para resolver links relativos. |
| useSlideWithIndexAsStart | Boolean | Esta bandeira determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

### Valor de Retorno

Slides adicionados.

### Veja Também

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlText | String | HTML a ser adicionado. |

### Valor de Retorno

Slides adicionados

### Veja Também

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlText | String | HTML a ser adicionado. |
| useSlideWithIndexAsStart | Boolean | Esta bandeira determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

### Valor de Retorno

Slides adicionados

### Veja Também

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlReader | TextReader | Objeto TextReader que será usado como fonte de um arquivo HTML. |
| resolver | IExternalResourceResolver | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | String | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de Retorno

Slides adicionados.

### Veja Também

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlReader | TextReader | Objeto TextReader que será usado como fonte de um arquivo HTML. |

### Valor de Retorno

Slides adicionados

### Veja Também

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlStream | Stream | Objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | IExternalResourceResolver | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | String | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de Retorno

Slides adicionados.

### Veja Também

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlStream | Stream | Objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | IExternalResourceResolver | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | String | Um URI do HTML especificado. Usado para resolver links relativos. |
| useSlideWithIndexAsStart | Boolean | Esta bandeira determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

### Valor de Retorno

Slides adicionados.

### Veja Também

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlStream | Stream | Objeto Stream que será usado como fonte de um arquivo HTML. |

### Valor de Retorno

Slides adicionados

### Veja Também

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Cria slides a partir de texto HTML e os insere na coleção na posição especificada.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | Int32 | Posição para inserção. |
| htmlStream | Stream | Objeto Stream que será usado como fonte de um arquivo HTML. |
| useSlideWithIndexAsStart | Boolean | Esta bandeira determina como iniciar a inserção: a partir de um novo slide ou a partir do slide com o índice especificado. Se **true**, a inserção de dados começará em um espaço vazio no slide com o índice especificado. Se **false**, os dados serão adicionados aos slides criados. |

### Valor de Retorno

Slides adicionados

### Veja Também

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->