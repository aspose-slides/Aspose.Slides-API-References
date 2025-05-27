---
title: AddFromHtml
second_title: Referencia de API de Aspose.Slides para .NET
description: Crea diapositivas desde texto HTML y las añade al final de la colección.
type: docs
weight: 70
url: /es/aspose.slides/slidecollection/addfromhtml/
---

## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Crea diapositivas desde texto HTML y las añade al final de la colección.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Par&aacute;metro | Tipo | Descripci&oacute;n |
| --- | --- | --- |
| htmlText | String | Html para agregar. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Se utiliza para resolver enlaces relativos. |

### Valor de Retorno

Diapositivas añadidas.

### Véase También

* interfaz [ISlide](../../islide)
* interfaz [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* clase [SlideCollection](../../slidecollection)
* espacio de nombres [Aspose.Slides](../../slidecollection)
* ensamblado [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Crea diapositivas desde texto HTML y las añade al final de la colección.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Par&aacute;metro | Tipo | Descripci&oacute;n |
| --- | --- | --- |
| htmlText | String | Html para agregar. |

### Valor de Retorno

Diapositivas añadidas.

### Véase También

* interfaz [ISlide](../../islide)
* clase [SlideCollection](../../slidecollection)
* espacio de nombres [Aspose.Slides](../../slidecollection)
* ensamblado [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Crea diapositivas desde texto HTML y las añade al final de la colección.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Par&aacute;metro | Tipo | Descripci&oacute;n |
| --- | --- | --- |
| htmlReader | TextReader | Objeto TextReader que se utilizará como fuente de un archivo HTML. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Se utiliza para resolver enlaces relativos. |

### Valor de Retorno

Diapositivas añadidas.

### Véase También

* interfaz [ISlide](../../islide)
* interfaz [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* clase [SlideCollection](../../slidecollection)
* espacio de nombres [Aspose.Slides](../../slidecollection)
* ensamblado [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Crea diapositivas desde texto HTML y las añade al final de la colección.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Par&aacute;metro | Tipo | Descripci&oacute;n |
| --- | --- | --- |
| htmlReader | TextReader | Objeto TextReader que se utilizará como fuente de un archivo HTML. |

### Valor de Retorno

Diapositivas añadidas.

### Véase También

* interfaz [ISlide](../../islide)
* clase [SlideCollection](../../slidecollection)
* espacio de nombres [Aspose.Slides](../../slidecollection)
* ensamblado [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Crea diapositivas desde texto HTML y las añade al final de la colección.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Par&aacute;metro | Tipo | Descripci&oacute;n |
| --- | --- | --- |
| htmlStream | Stream | Un objeto Stream que se utilizará como fuente de un archivo HTML. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Se utiliza para resolver enlaces relativos. |

### Valor de Retorno

Diapositivas añadidas.

### Véase También

* interfaz [ISlide](../../islide)
* interfaz [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* clase [SlideCollection](../../slidecollection)
* espacio de nombres [Aspose.Slides](../../slidecollection)
* ensamblado [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Crea diapositivas desde texto HTML y las añade al final de la colección.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Par&aacute;metro | Tipo | Descripci&oacute;n |
| --- | --- | --- |
| htmlStream | Stream | Un objeto Stream que se utilizará como fuente de un archivo HTML. |

### Valor de Retorno

Diapositivas añadidas.

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
	// Utilizar el método Save para guardar el archivo como un documento de PowerPoint.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Véase También

* interfaz [ISlide](../../islide)
* clase [SlideCollection](../../slidecollection)
* espacio de nombres [Aspose.Slides](../../slidecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->