---
title: InsertFromHtml
second_title: Aspose.Sildes voor .NET API Referentie
description: Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.
type: docs
weight: 140
url: /nl/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlText | String | HTML om toe te voegen. |
| resolver | IExternalResourceResolver | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

### Zie ook

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlText | String | HTML om toe te voegen. |
| resolver | IExternalResourceResolver | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |
| useSlideWithIndexAsStart | Boolean | Deze vlag bepaalt hoe de invoeging moet starten: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, dan begint de gegevensinvoeging in een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia's. |

### Retourwaarde

Toegevoegde dia's.

### Zie ook

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlText | String | HTML om toe te voegen. |

### Retourwaarde

Toegevoegde dia's

### Zie ook

* interface [ISlide](../../islide)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlText | String | HTML om toe te voegen. |
| useSlideWithIndexAsStart | Boolean | Deze vlag bepaalt hoe de invoeging moet starten: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, dan begint de gegevensinvoeging in een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia's. |

### Retourwaarde

Toegevoegde dia's

### Zie ook

* interface [ISlide](../../islide)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlReader | TextReader | TextReader-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | IExternalResourceResolver | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

### Zie ook

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlReader | TextReader | TextReader-object dat wordt gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's

### Zie ook

* interface [ISlide](../../islide)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlStream | Stream | Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | IExternalResourceResolver | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |

### Retourwaarde

Toegevoegde dia's.

### Zie ook

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlStream | Stream | Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | IExternalResourceResolver | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |
| useSlideWithIndexAsStart | Boolean | Deze vlag bepaalt hoe de invoeging moet starten: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, dan begint de gegevensinvoeging in een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia's. |

### Retourwaarde

Toegevoegde dia's.

### Zie ook

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlStream | Stream | Stream-object dat wordt gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's

### Zie ook

* interface [ISlide](../../islide)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Maakt dia's van HTML-tekst en voegt ze in de collectie in op de opgegeven positie.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Positie om in te voegen. |
| htmlStream | Stream | Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| useSlideWithIndexAsStart | Boolean | Deze vlag bepaalt hoe de invoeging moet starten: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, dan begint de gegevensinvoeging in een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia's. |

### Retourwaarde

Toegevoegde dia's

### Zie ook

* interface [ISlide](../../islide)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->