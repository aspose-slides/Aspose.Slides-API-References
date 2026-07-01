---
title: InsertFromHtml
second_title: Aspose.Sildes pro .NET API Reference
description: Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.
type: docs
weight: 140
url: /cs/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlText | String | Html k přidání. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný pro načítání externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlText | String | Html k přidání. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný pro načítání externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | Boolean | Toto označení určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vložení dat začne na prázdném místě ve snímku se zadaným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlText | String | Html k přidání. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlText | String | Html k přidání. |
| useSlideWithIndexAsStart | Boolean | Toto označení určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vložení dat začne na prázdném místě ve snímku se zadaným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlReader | TextReader | Objekt TextReader, který bude použit jako zdroj HTML souboru. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný pro načítání externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlReader | TextReader | Objekt TextReader, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlStream | Stream | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný pro načítání externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlStream | Stream | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný pro načítání externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| uri | String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | Boolean | Toto označení určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vložení dat začne na prázdném místě ve snímku se zadaným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlStream | Stream | Objekt Stream, který bude použit jako zdroj HTML souboru. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Vytváří snímky z HTML textu a vkládá je do kolekce na zadané pozici.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlStream | Stream | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| useSlideWithIndexAsStart | Boolean | Toto označení určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vložení dat začne na prázdném místě ve snímku se zadaným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* třída [SlideCollection](../../slidecollection)
* jmenný prostor [Aspose.Slides](../../slidecollection)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->