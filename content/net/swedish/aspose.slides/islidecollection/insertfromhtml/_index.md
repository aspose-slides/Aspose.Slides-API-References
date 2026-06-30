---
title: InsertFromHtml
second_title: Aspose.Sildes för .NET API-referens
description: Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.
type: docs
weight: 90
url: /sv/aspose.slides/islidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlText | String | HTML att lägga till. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om detta argument är null kommer alla externa objekt att ignoreras. |
| uri | String | En URI för den specificerade HTML-koden. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

### Se också

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlText | String | HTML att lägga till. |

### Returvärde

Tillagda bilder

### Se också

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlReader | TextReader | TextReader-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om detta argument är null kommer alla externa objekt att ignoreras. |
| uri | String | En URI för den specificerade HTML-koden. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

### Se också

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlReader | TextReader | TextReader-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

### Se också

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlStream | Stream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om detta argument är null kommer alla externa objekt att ignoreras. |
| uri | String | En URI för den specificerade HTML-koden. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

### Se också

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlStream | Stream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

### Se också

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlText | String | HTML att lägga till. |
| useSlideWithIndexAsStart | Boolean | Denna flagga bestämmer hur infogningen ska påbörjas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar datainfogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder

### Se också

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlText | String | HTML att lägga till. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om detta argument är null kommer alla externa objekt att ignoreras. |
| uri | String | En URI för den specificerade HTML-koden. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | Boolean | Denna flagga bestämmer hur infogningen ska påbörjas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar datainfogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder.

### Se också

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlStream | Stream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| useSlideWithIndexAsStart | Boolean | Denna flagga bestämmer hur infogningen ska påbörjas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar datainfogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder

### Se också

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Position att infoga. |
| htmlStream | Stream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om detta argument är null kommer alla externa objekt att ignoreras. |
| uri | String | En URI för den specificerade HTML-koden. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | Boolean | Denna flagga bestämmer hur infogningen ska påbörjas: från en ny bild eller från bilden med det angivna indexet. Om **true** startar datainfogning från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till de skapade bilderna. |

### Returvärde

Tillagda bilder.

### Se också

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->