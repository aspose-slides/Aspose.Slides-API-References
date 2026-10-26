---
title: InsertFromHtml
second_title: Aspose.Sildes pro .NET API Reference
description: Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.
type: docs
weight: 90
url: /cs/aspose.slides/islidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlText | String | HTML k přidání. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | String | URI zadaného HTML. Používá se k rozlišení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlText | String | HTML k přidání. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlReader | TextReader | Objekt TextReader, který bude použit jako zdroj HTML souboru. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | String | URI zadaného HTML. Používá se k rozlišení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

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
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlStream | Stream | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | String | URI zadaného HTML. Používá se k rozlišení relativních odkazů. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

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
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlText | String | HTML k přidání. |
| useSlideWithIndexAsStart | Boolean | Tento příznak určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vložení dat začne na prázdném místě na snímku se zadaným indexem. Pokud je **false**, data budou přidána k vytvořeným snímkům. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlText | String | HTML k přidání. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | String | URI zadaného HTML. Používá se k rozlišení relativních odkazů. |
| useSlideWithIndexAsStart | Boolean | Tento příznak určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vložení dat začne na prázdném místě na snímku se zadaným indexem. Pokud je **false**, data budou přidána k vytvořeným snímkům. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlStream | Stream | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| useSlideWithIndexAsStart | Boolean | Tento příznak určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vložení dat začne na prázdném místě na snímku se zadaným indexem. Pokud je **false**, data budou přidána k vytvořeným snímkům. |

### Návratová hodnota

Přidané snímky

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Vytvoří snímky z HTML textu a vloží je do kolekce na zadanou pozici.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | Int32 | Pozice pro vložení. |
| htmlStream | Stream | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | IExternalResourceResolver | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | String | URI zadaného HTML. Používá se k rozlišení relativních odkazů. |
| useSlideWithIndexAsStart | Boolean | Tento příznak určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, vložení dat začne na prázdném místě na snímku se zadaným indexem. Pokud je **false**, data budou přidána k vytvořeným snímkům. |

### Návratová hodnota

Přidané snímky.

### Viz také

* rozhraní [ISlide](../../islide)
* rozhraní [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* rozhraní [ISlideCollection](../../islidecollection)
* obor názvů [Aspose.Slides](../../islidecollection)
* sestava [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->