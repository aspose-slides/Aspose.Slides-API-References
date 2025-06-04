---
title: AddFromHtml
second_title: Aspose.Sildes for .NET API Referenz
description: Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.
type: docs
weight: 70
url: /de/aspose.slides/slidecollection/addfromhtml/
---

## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | String | Hinzuzufügendes HTML. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
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

## AddFromHtml(string) {#addfromhtml_4}

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | String | Hinzuzufügendes HTML. |

### Rückgabewert

Hinzugefügte Folien

### Siehe Auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlReader | TextReader | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
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

## AddFromHtml(TextReader) {#addfromhtml_2}

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlReader | TextReader | TextReader-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien

### Siehe Auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
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

## AddFromHtml(Stream) {#addfromhtml}

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

### Rückgabewert

Hinzugefügte Folien

### Beispiele

```csharp
[C#]
// Erstellen Sie eine Instanz der Presentation-Klasse.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Rufen Sie die Methode AddFromHtml auf und übergeben Sie die HTML-Datei.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Verwenden Sie die Methode Save, um die Datei als PowerPoint-Dokument zu speichern.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Siehe Auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->