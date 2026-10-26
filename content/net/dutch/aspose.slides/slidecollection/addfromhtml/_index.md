---
title: AddFromHtml
second_title: Aspose.Sildes voor .NET API Referentie
description: Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.
type: docs
weight: 70
url: /nl/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlText | String | Html om toe te voegen. |
| resolver | IExternalResourceResolver | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen te resolven. |

### Retourwaarde

Toegevoegde dia's.

### Zie ook

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlText | String | Html om toe te voegen. |

### Retourwaarde

Toegevoegde dia's

### Zie ook

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlReader | TextReader | TextReader-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | IExternalResourceResolver | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen te resolven. |

### Retourwaarde

Toegevoegde dia's.

### Zie ook

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlReader | TextReader | TextReader-object dat wordt gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's

### Zie ook

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlStream | Stream | Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | IExternalResourceResolver | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen te resolven. |

### Retourwaarde

Toegevoegde dia's.

### Zie ook

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlStream | Stream | Stream-object dat wordt gebruikt als bron van een HTML-bestand. |

### Retourwaarde

Toegevoegde dia's

### Voorbeelden

```csharp
[C#]
// Maak een instantie van de Presentation-klasse.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Roep de AddFromHtml-methode aan en geef het HTML-bestand door.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Gebruik de Save-methode om het bestand op te slaan als een PowerPoint-document.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->