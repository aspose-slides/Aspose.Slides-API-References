---
title: InsertFromHtml
second_title: Aspose.Slides für .NET API Referenz
description: Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.
type: docs
weight: 140
url: /de/aspose.slides/slidecollection/insertfromhtml/
---

## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlText | String | HTML, das hinzugefügt werden soll. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte abzurufen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlText | String | HTML, das hinzugefügt werden soll. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte abzurufen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |
| useSlideWithIndexAsStart | Boolean | Dieses Flag bestimmt, wie die Einfügung gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt die Dateneinfügung von einem leeren Bereich auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlText | String | HTML, das hinzugefügt werden soll. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlText | String | HTML, das hinzugefügt werden soll. |
| useSlideWithIndexAsStart | Boolean | Dieses Flag bestimmt, wie die Einfügung gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt die Dateneinfügung von einem leeren Bereich auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlReader | TextReader | TextReader-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte abzurufen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlReader | TextReader | TextReader-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte abzurufen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte abzurufen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |
| useSlideWithIndexAsStart | Boolean | Dieses Flag bestimmt, wie die Einfügung gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt die Dateneinfügung von einem leeren Bereich auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Position zum Einfügen. |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |
| useSlideWithIndexAsStart | Boolean | Dieses Flag bestimmt, wie die Einfügung gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt die Dateneinfügung von einem leeren Bereich auf der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

### Rückgabewert

Hinzugefügte Folien.

### Siehe Auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->