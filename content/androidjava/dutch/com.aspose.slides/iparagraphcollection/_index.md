---
title: IParagraphCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van alinea's voor.
type: docs
url: /nl/com.aspose.slides/iparagraphcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Stelt een collectie van alinea's voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op de gespecificeerde index op. |
| [getCount()](#getCount--) | Haalt het werkelijke aantal elementen in de collectie op. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Voegt een Paragraph toe aan het einde van de collectie. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Voegt een inhoud van ParagraphCollection toe aan het einde van de collectie. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Voegt een Paragraph in de collectie in op de opgegeven index. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Voegt een inhoud van ParagraphCollection in de collectie in op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Verwijdert de eerste verschijning van een specifieke alinea. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Voegt tekst van een opgegeven html-tekenreeks toe aan de collectie. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Voegt tekst van een opgegeven html-tekenreeks toe aan de collectie. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Converteert opgegeven alinea's naar HTML en retourneert het als een String-object. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Haalt het element op de gespecificeerde index op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

**Retour:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Voegt een Paragraph toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | De Paragraph die aan het einde van de collectie moet worden toegevoegd. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Voegt een inhoud van ParagraphCollection toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | De ParagraphCollection die aan het einde van de collectie moet worden toegevoegd. |

**Retour:**
int - De index waarop de Paragraph is toegevoegd of -1 als er niets toe te voegen is.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Voegt een Paragraph in de collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de Paragraph moet worden ingevoegd. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | De Paragraph om in te voegen. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Voegt een inhoud van ParagraphCollection in de collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop alinea's moeten worden ingevoegd. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | De alinea's om in te voegen. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle elementen uit de collectie.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Verwijdert de eerste verschijning van een specifieke alinea.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | De alinea die uit de collectie moet worden verwijderd. |

**Retour:**
boolean - true als het item succesvol is verwijderd; anders false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Voegt tekst van een opgegeven html-tekenreeks toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | HTML-tekst. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Voegt tekst van een opgegeven html-tekenreeks toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | HTML-tekst. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver callback-object dat URI’s oplost en gerefereerde objecten ophaalt. |
| uri | java.lang.String | URI voor het toevoegen van een HTML-document. Wordt gebruikt voor het oplossen van relatieve koppelingen. |

--------------------

Het specificeren van een resolver kan potentieel een kwetsbaarheid introduceren. Gebruik met voorzichtigheid. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Converteert opgegeven alinea's naar HTML en retourneert het als een String-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| firstParagraphIndex | int | Eerste alinea-index int |
| paragraphsCount | int | Aantal alinea's int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Conversie-opties [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Retour:**
java.lang.String - Gegenereerde HTML.