---
title: InsertFromHtml
second_title: Aspose.Slides für .NET API Referenz
description: Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.
type: docs
weight: 140
url: /de/aspose.slides/slidecollection/insertfromhtml/
---

## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlText | String | HTML zum Hinzufügen. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte zu holen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlText | String | HTML zum Hinzufügen. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte zu holen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |
| useSlideWithIndexAsStart | Boolean | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen von Daten von einem leeren Bereich auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlText | String | HTML zum Hinzufügen. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlText | String | HTML zum Hinzufügen. |
| useSlideWithIndexAsStart | Boolean | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen von Daten von einem leeren Bereich auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlReader | TextReader | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte zu holen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlReader | TextReader | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte zu holen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte zu holen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |
| useSlideWithIndexAsStart | Boolean | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen von Daten von einem leeren Bereich auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Erschafft Folien aus HTML-Text und fügt sie an der angegebenen Position zur Sammlung hinzu.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| useSlideWithIndexAsStart | Boolean | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt das Einfügen von Daten von einem leeren Bereich auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* Interface [ISlide](../../islide)
* Klasse [SlideCollection](../../slidecollection)
* Namespace [Aspose.Slides](../../slidecollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->