---
title: AddFromHtml
second_title: Aspose.Sildes for .NET API Reference
description: Creates slides from HTML text and adds them to the end of the collection.
type: docs
weight: 70
url: /net/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Creates slides from HTML text and adds them to the end of the collection.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |
| resolver | IExternalResourceResolver | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

### Return Value

Added slides.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Creates slides from HTML text and adds them to the end of the collection.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |

### Return Value

Added slides

### See Also

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Creates slides from HTML text and adds them to the end of the collection.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | TextReader | TextReader object which will be used as a source of a HTML file. |
| resolver | IExternalResourceResolver | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

### Return Value

Added slides.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Creates slides from HTML text and adds them to the end of the collection.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | TextReader | TextReader object which will be used as a source of a HTML file. |

### Return Value

Added slides

### See Also

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Creates slides from HTML text and adds them to the end of the collection.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | Stream | A Stream object which will be used as a source of a HTML file. |
| resolver | IExternalResourceResolver | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

### Return Value

Added slides.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Creates slides from HTML text and adds them to the end of the collection.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | Stream | A Stream object which will be used as a source of a HTML file. |

### Return Value

Added slides

### Examples

```csharp
[C#]
// Create an instance of the Presentation class.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Call the AddFromHtml method and pass the HTML file.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Use the Save method to save the file as a PowerPoint document.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
