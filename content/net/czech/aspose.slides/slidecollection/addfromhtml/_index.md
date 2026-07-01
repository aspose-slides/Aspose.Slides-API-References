---
title: AddFromHtml
second_title: Aspose.Sildes pro .NET API Reference
description: Vytvoří snímky z HTML textu a přidá je na konec kolekce.
type: docs
weight: 70
url: /cs/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | String | HTML k přidání. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | String | URI specifikovaného HTML. Používá se k vyřešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | String | HTML k přidání. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlReader | TextReader | Objekt TextReader, který bude použit jako zdroj HTML souboru. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | String | URI specifikovaného HTML. Používá se k vyřešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlReader | TextReader | Objekt TextReader, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | Stream | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | String | URI specifikovaného HTML. Používá se k vyřešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | Stream | Objekt Stream, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky

### Příklady

```csharp
[C#]
// Vytvořte instanci třídy Presentation.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Zavolejte metodu AddFromHtml a předáte HTML soubor.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Použijte metodu Save k uložení souboru jako dokument PowerPoint.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [ISlide](../../islide)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->