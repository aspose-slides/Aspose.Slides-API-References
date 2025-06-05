---
title: AddFromHtml
second_title: Aspose.Slides para .NET API Reference
description: Crea diapositivas a partir de texto HTML y las agrega al final de la colección.
type: docs
weight: 70
url: /es/aspose.slides/slidecollection/addfromhtml/
---

## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlText | String | Html a agregar. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Se utiliza para resolver enlaces relativos. |

### Valor de Retorno

Diapositivas agregadas.

### Ver También

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlText | String | Html a agregar. |

### Valor de Retorno

Diapositivas agregadas

### Ver También

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlReader | TextReader | Objeto TextReader que se utilizará como fuente de un archivo HTML. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Se utiliza para resolver enlaces relativos. |

### Valor de Retorno

Diapositivas agregadas.

### Ver También

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlReader | TextReader | Objeto TextReader que se utilizará como fuente de un archivo HTML. |

### Valor de Retorno

Diapositivas agregadas

### Ver También

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlStream | Stream | Un objeto Stream que se utilizará como fuente de un archivo HTML. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Se utiliza para resolver enlaces relativos. |

### Valor de Retorno

Diapositivas agregadas.

### Ver También

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlStream | Stream | Un objeto Stream que se utilizará como fuente de un archivo HTML. |

### Valor de Retorno

Diapositivas agregadas

### Ejemplos

```csharp
[C#]
// Crear una instancia de la clase Presentation.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Llamar al método AddFromHtml y pasar el archivo HTML.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Usar el método Save para guardar el archivo como documento de PowerPoint.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->