---
title: IParagraphCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje kolekci odstavců.
type: docs
url: /cs/com.aspose.slides/iparagraphcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Represents a collection of a paragraphs.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getCount()](#getCount--) | Získá počet prvků, které jsou ve skutečnosti obsaženy v kolekci. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Přidá Paragraph na konec kolekce. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Přidá obsah ParagraphCollection na konec kolekce. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Vloží Paragraph do kolekce na zadaném indexu. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Vloží obsah ParagraphCollection do kolekce na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu kolekce. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Odstraní první výskyt konkrétního odstavce. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Přidá text ze zadaného řetězce html do kolekce. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Přidá text ze zadaného řetězce html do kolekce. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Převede určené odstavce do HTML a vrátí je jako objekt String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


Získá prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Získá počet prvků, které jsou ve skutečnosti obsaženy v kolekci. Read-only int.

**Vrací:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


Přidá Paragraph na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, který bude přidán na konec kolekce. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


Přidá obsah ParagraphCollection na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection, který bude přidán na konec kolekce. |

**Vrací:**
int - Index, na který byl Paragraph přidán, nebo -1 pokud není nic k přidání.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


Vloží Paragraph do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se má Paragraph vložit. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, který se má vložit. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


Vloží obsah ParagraphCollection do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na který se mají odstavce vložit. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Odstavce k vložení. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny prvky z kolekce.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní prvek na zadaném indexu kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který se má odstranit. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


Odstraní první výskyt konkrétního odstavce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Odstavec, který se má odstranit z kolekce. |

**Vrací:**
boolean - true pokud byl prvek úspěšně odstraněn; jinak false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


Přidá text ze zadaného řetězce html do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | HTML text. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Přidá text ze zadaného řetězce html do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | HTML text. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání resolveru, který řeší URI a získává odkazované objekty. |
| uri | java.lang.String | URI pro přidání HTML dokumentu. Používá se k řešení relativních odkazů.

Specifikace resolveru může potenciálně způsobit zranitelnost. Používejte opatrně. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


Převede určené odstavce do HTML a vrátí je jako objekt String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| firstParagraphIndex | int | Index prvního odstavce int |
| paragraphsCount | int | Počet odstavců int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Možnosti převodu [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Vrací:**
java.lang.String - Vygenerované HTML.