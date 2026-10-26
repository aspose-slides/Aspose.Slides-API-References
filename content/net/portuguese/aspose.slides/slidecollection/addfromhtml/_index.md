---
title: AddFromHtml
second_title: Aspose.Sildes para .NET Referência da API
description: Cria slides a partir de texto HTML e os adiciona ao final da coleção.
type: docs
weight: 70
url: /pt/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlText | String | Html a ser adicionado. |
| resolver | IExternalResourceResolver | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | String | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de Retorno

Slides adicionados.

### Ver também

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlText | String | Html a ser adicionado. |

### Valor de Retorno

Slides adicionados

### Ver também

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlReader | TextReader | Objeto TextReader que será usado como fonte de um arquivo HTML. |
| resolver | IExternalResourceResolver | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | String | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de Retorno

Slides adicionados.

### Ver também

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlReader | TextReader | Objeto TextReader que será usado como fonte de um arquivo HTML. |

### Valor de Retorno

Slides adicionados

### Ver também

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlStream | Stream | Um objeto Stream que será usado como fonte de um arquivo HTML. |
| resolver | IExternalResourceResolver | Um objeto de retorno de chamada usado para buscar objetos externos. Se este parâmetro for nulo, todos os objetos externos serão ignorados. |
| uri | String | Um URI do HTML especificado. Usado para resolver links relativos. |

### Valor de Retorno

Slides adicionados.

### Ver também

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Cria slides a partir de texto HTML e os adiciona ao final da coleção.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlStream | Stream | Um objeto Stream que será usado como fonte de um arquivo HTML. |

### Valor de Retorno

Slides adicionados

### Exemplos

```csharp
[C#]
// Crie uma instância da classe Presentation.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Chame o método AddFromHtml e passe o arquivo HTML.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Use o método Save para salvar o arquivo como um documento PowerPoint.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Ver também

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->