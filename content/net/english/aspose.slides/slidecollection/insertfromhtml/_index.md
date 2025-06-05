---
title: InsertFromHtml
second_title: Aspose.Sildes for .NET API Reference
description: Creates slides from HTML text and inserts them to the collection at the specified position.
type: docs
weight: 140
url: /aspose.slides/slidecollection/insertfromhtml/
---

## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
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

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
| htmlText | String | Html to add. |
| resolver | IExternalResourceResolver | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| useSlideWithIndexAsStart | Boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

### Return Value

Added slides.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
| htmlText | String | Html to add. |

### Return Value

Added slides

### See Also

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
| htmlText | String | Html to add. |
| useSlideWithIndexAsStart | Boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

### Return Value

Added slides

### See Also

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
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

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
| htmlReader | TextReader | TextReader object which will be used as a source of a HTML file. |

### Return Value

Added slides

### See Also

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
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

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
| htmlStream | Stream | A Stream object which will be used as a source of a HTML file. |
| resolver | IExternalResourceResolver | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| useSlideWithIndexAsStart | Boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

### Return Value

Added slides.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
| htmlStream | Stream | A Stream object which will be used as a source of a HTML file. |

### Return Value

Added slides

### See Also

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Creates slides from HTML text and inserts them to the collection at the specified position.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position to insert. |
| htmlStream | Stream | A Stream object which will be used as a source of a HTML file. |
| useSlideWithIndexAsStart | Boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

### Return Value

Added slides

### See Also

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
