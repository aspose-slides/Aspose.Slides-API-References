---
title: AddFromHtml
second_title: Aspose.Slides für .NET API Referenz
description: Erstellt Folien aus HTML-Text und fügt sie ans Ende der Sammlung hinzu.
type: docs
weight: 70
url: /de/aspose.slides/slidecollection/addfromhtml/
---

## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Erstellt Folien aus HTML-Text und fügt sie ans Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | String | Hinzuzufügender HTML-Text. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte abzurufen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTMLs. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Erstellt Folien aus HTML-Text und fügt sie ans Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | String | Hinzuzufügender HTML-Text. |

### Rückgabewert

Hinzufügte Folien

### Siehe auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Erstellt Folien aus HTML-Text und fügt sie ans Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlReader | TextReader | TextReader-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte abzurufen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTMLs. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Erstellt Folien aus HTML-Text und fügt sie ans Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlReader | TextReader | TextReader-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |

### Rückgabewert

Hinzufügte Folien

### Siehe auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Erstellt Folien aus HTML-Text und fügt sie ans Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |
| resolver | IExternalResourceResolver | Ein Callback-Objekt, das verwendet wird, um externe Objekte abzurufen. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | String | Eine URI des angegebenen HTMLs. Wird verwendet, um relative Links aufzulösen. |

### Rückgabewert

Hinzufügte Folien.

### Siehe auch

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Erstellt Folien aus HTML-Text und fügt sie ans Ende der Sammlung hinzu.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | Stream | Ein Stream-Objekt, das als Quelle für eine HTML-Datei verwendet wird. |

### Rückgabewert

Hinzufügte Folien

### Beispiel

```csharp
[C#]
// Erstellen Sie eine Instanz der Präsentationsklasse.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Rufen Sie die AddFromHtml-Methode auf und übergeben Sie die HTML-Datei.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Verwenden Sie die Save-Methode, um die Datei als PowerPoint-Dokument zu speichern.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->