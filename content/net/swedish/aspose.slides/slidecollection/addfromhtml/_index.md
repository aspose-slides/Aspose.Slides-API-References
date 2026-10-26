---
title: AddFromHtml
second_title: Aspose.Sildes för .NET API-referens
description: Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.
type: docs
weight: 70
url: /sv/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | String | Html att lägga till. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null kommer alla externa objekt att ignoreras. |
| uri | String | En URI för den angivna HTML-en. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

### Se även

* gränssnitt [ISlide](../../islide)
* gränssnitt [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klass [SlideCollection](../../slidecollection)
* namnrymd [Aspose.Slides](../../slidecollection)
* samling [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | String | Html att lägga till. |

### Returvärde

Tillagda bilder

### Se även

* gränssnitt [ISlide](../../islide)
* klass [SlideCollection](../../slidecollection)
* namnrymd [Aspose.Slides](../../slidecollection)
* samling [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlReader | TextReader | TextReader-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null kommer alla externa objekt att ignoreras. |
| uri | String | En URI för den angivna HTML-en. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

### Se även

* gränssnitt [ISlide](../../islide)
* gränssnitt [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klass [SlideCollection](../../slidecollection)
* namnrymd [Aspose.Slides](../../slidecollection)
* samling [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlReader | TextReader | TextReader-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

### Se även

* gränssnitt [ISlide](../../islide)
* klass [SlideCollection](../../slidecollection)
* namnrymd [Aspose.Slides](../../slidecollection)
* samling [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | Stream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | IExternalResourceResolver | Ett återuppringningsobjekt som används för att hämta externa objekt. Om denna parameter är null kommer alla externa objekt att ignoreras. |
| uri | String | En URI för den angivna HTML-en. Används för att lösa relativa länkar. |

### Returvärde

Tillagda bilder.

### Se även

* gränssnitt [ISlide](../../islide)
* gränssnitt [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* klass [SlideCollection](../../slidecollection)
* namnrymd [Aspose.Slides](../../slidecollection)
* samling [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | Stream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |

### Returvärde

Tillagda bilder

### Exempel

```csharp
[C#]
// Skapa en instans av Presentation-klassen.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Anropa AddFromHtml-metoden och skicka med HTML-filen.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Använd Save-metoden för att spara filen som ett PowerPoint-dokument.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [ISlide](../../islide)
* klass [SlideCollection](../../slidecollection)
* namnrymd [Aspose.Slides](../../slidecollection)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->