---
title: IParagraphCollection
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje kolekci odstavců.
type: docs
url: /cs/com.aspose.slides/iparagraphcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Reprezentuje kolekci odstavců.
## Methods

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getCount()](#getCount--) | Získá počet prvků, které jsou ve skutečnosti obsaženy v kolekci. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Přidá Paragraph na konec kolekce. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Přidá obsah ParagraphCollection na konec kolekce. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Vloží Paragraph do kolekce na zadaný index. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Vloží obsah ParagraphCollection do kolekce na zadaný index. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu kolekce. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Odstraní první výskyt konkrétního odstavce. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Přidá text ze zadaného HTML řetězce do kolekce. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Přidá text ze zadaného HTML řetězce do kolekce. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Převádí určené odstavce do HTML a vrátí je jako objekt String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


Získá prvek na zadaném indexu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Získá počet prvků, které jsou ve skutečnosti obsaženy v kolekci. int pouze ke čtení.

**Návratová hodnota:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


Přidá Paragraph na konec kolekce.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, který se má přidat na konec kolekce. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


Přidá obsah ParagraphCollection na konec kolekce.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection, který se má přidat na konec kolekce. |

**Návratová hodnota:**
int – Index, na který byl Paragraph přidán, nebo -1 pokud není co přidat.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


Vloží Paragraph do kolekce na zadaný index.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Nulový index, na který se má Paragraph vložit. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, který se má vložit. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


Vloží obsah ParagraphCollection do kolekce na zadaný index.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Nulový index, na který se mají vložit odstavce. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Odrstavce, které se mají vložit. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Nulový index prvku, který se má odstranit. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


Odstraní první výskyt konkrétního odstavce.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Odsavtek, který se má odebrat z kolekce. |

**Návratová hodnota:**
boolean – true, pokud byl prvek úspěšně odebrán; jinak false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


Přidá text ze zadaného HTML řetězce do kolekce.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | HTML text. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Přidá text ze zadaného HTML řetězce do kolekce.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | HTML text. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání resolveru, který řeší URI a načítá odkazované objekty. |
| uri | java.lang.String | URI pro přidání HTML dokumentu. Používá se k řešení relativních odkazů.

--------------------

Určení resolveru může potenciálně představovat zranitelnost. Používejte s opatrností. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


Převádí určené odstavce do HTML a vrátí je jako objekt String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | Index prvního odstavce |
| paragraphsCount | int | Počet odstavců |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Možnosti konverze [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Návratová hodnota:**
java.lang.String – Vygenerované HTML.