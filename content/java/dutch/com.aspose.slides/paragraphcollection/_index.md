---
title: ParagraphCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie van alinea's voor.
type: docs
url: /nl/com.aspose.slides/paragraphcollection/
---
**Overerving:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Stelt een collectie van Paragraphs voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [isReadOnly()](#isReadOnly--) | Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Voegt een Paragraph toe aan het einde van de collectie. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Voegt de inhoud van ParagraphCollection toe aan het einde van de collectie. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Bepaalt de index van een specifiek item in de List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Voegt een Paragraph in de collectie in op de opgegeven index. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Voegt de inhoud van ParagraphCollection in de collectie in op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend bij een bepaalde Array-index. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index uit de collectie. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Verwijdert de eerste voorkomen van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java iterator voor de gehele collectie. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende slide van een Paragraphs-collectie. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een Paragraphs-collectie. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Voegt tekst van de opgegeven html-string toe aan de collectie. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Voegt tekst van de opgegeven html-string toe aan de collectie. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Converteert opgegeven Paragraphs naar HTML en retourneert het als String-object. |

### getCount() {#getCount--}
```
public final int getCount()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen int.

**Retourneert:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. Alleen-lezen boolean.

**Retourneert:**
boolean - true als de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is; anders false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Voegt een Paragraph toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | De Paragraph die aan het einde van de collectie moet worden toegevoegd. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Voegt de inhoud van ParagraphCollection toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | De ParagraphCollection die aan het einde van de collectie moet worden toegevoegd. |

**Retourneert:**
int - De index waarop de Paragraph is toegevoegd of -1 als er niets toe te voegen is.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Bepaalt de index van een specifiek item in de List.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Het object om te vinden in de List. |

**Retourneert:**
int - De index van het item als het in de lijst is gevonden; anders -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Voegt een Paragraph in de collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop Paragraph moet worden ingevoegd. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | De Paragraph die moet worden ingevoegd. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Voegt de inhoud van ParagraphCollection in de collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop alinea's moeten worden ingevoegd. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | De ParagraphCollection die moet worden ingevoegd. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle elementen uit de collectie.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Het object om te vinden in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retourneert:**
boolean - true als het item is gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend bij een bepaalde Array-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | De eendimensionale Array die de bestemming is voor de elementen gekopieerd van [IGenericCollection](../../com.aspose.slides/igenericcollection). De Array moet nul-gebaseerde indexering hebben. |
| arrayIndex | int | De nul-gebaseerde index in de array waarop het kopiëren begint. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Verwijdert de eerste voorkomen van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Het object om te verwijderen uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retourneert:**
boolean - true als het item met succes is verwijderd uit de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false. Deze methode retourneert ook false als het item niet wordt gevonden in de originele [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Retourneert een java iterator voor de gehele collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Een java.util.Iterator voor de gehele collectie.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende slide van een Paragraphs-collectie. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een Paragraphs-collectie. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Voegt tekst van de opgegeven html-string toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | HTML-tekst. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Voegt tekst van de opgegeven html-string toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | HTML-tekst. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver callback-object dat URIs oplost en verwijzende objecten ophaalt. |
| uri | java.lang.String | URI voor het toevoegen van een HTML-document. Wordt gebruikt voor het oplossen van relatieve links. |

--------------------
Het specificeren van een resolver kan potentieel een kwetsbaarheid introduceren. Gebruik met voorzichtigheid.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Converteert opgegeven Paragraphs naar HTML en retourneert het als String-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| firstParagraphIndex | int | Eerste alinea-index int |
| paragraphsCount | int | Aantal alinea's int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Conversie-opties [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Retourneert:**
java.lang.String - Gegenereerde HTML.