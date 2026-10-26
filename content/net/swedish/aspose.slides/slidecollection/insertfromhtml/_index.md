---
title: InsertFromHtml
second_title: Aspose.Slides för .NET API-referens
description: Skapar bilder från HTML-text och lägger till dem i samlingen på den angivna positionen.
type: docs
weight: 140
url: /sv/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlText | String | HTML att lägga till. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | String | En URI för den angivna HTML. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

### Se även

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlText | String | HTML att lägga till. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | String | En URI för den angivna HTML. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | Boolean | Denna flagga bestämmer hur infogningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar datainfogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder.

### Se även

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlText | String | HTML att lägga till. |

### Returvärde

Tillagda bilder

### Se även

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlText | String | HTML att lägga till. |
| useSlideWithIndexAsStart | Boolean | Denna flagga bestämmer hur infogningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar datainfogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder

### Se även

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlReader | TextReader | TextReader-objekt som används som källa för en HTML-fil. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | String | En URI för den angivna HTML. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

### Se även

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlReader | TextReader | TextReader-objekt som används som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

### Se även

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlStream | Stream | Ett Stream-objekt som används som källa för en HTML-fil. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | String | En URI för den angivna HTML. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

### Se även

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlStream | Stream | Ett Stream-objekt som används som källa för en HTML-fil. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null ignoreras alla externa objekt. |
| uri | String | En URI för den angivna HTML. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | Boolean | Denna flagga bestämmer hur infogningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar datainfogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder.

### Se även

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlStream | Stream | Ett Stream-objekt som används som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

### Se även

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Skapar bilder från HTML-text och placerar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlStream | Stream | Ett Stream-objekt som används som källa för en HTML-fil. |
| useSlideWithIndexAsStart | Boolean | Denna flagga bestämmer hur infogningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar datainfogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder

### Se även

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->