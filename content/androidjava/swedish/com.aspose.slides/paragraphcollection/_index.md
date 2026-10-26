---
title: ParagraphCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av stycken.
type: docs
url: /sv/com.aspose.slides/paragraphcollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Representerar en samling av stycken.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [isReadOnly()](#isReadOnly--) | Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Lägger till ett Paragraph i slutet av samlingen. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Lägger till ett innehåll av ParagraphCollection i slutet av samlingen. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Bestämmer indexet för ett specifikt objekt i List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Infogar ett Paragraph i samlingen på det angivna indexet. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Infogar ett innehåll av ParagraphCollection i samlingen på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med början vid ett specifikt Array-index. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Tar bort den första förekomsten av ett specifikt objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [getSlide()](#getSlide--) | Returnerar den överordnade slide för en paragraphs-samling. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för en paragraphs-samling. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Lägger till text från angiven HTML-sträng till samlingen. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Lägger till text från angiven HTML-sträng till samlingen. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Konverterar angivna stycken till HTML och returnerar det som ett String-objekt. |
### getCount() {#getCount--}
```
public final int getCount()
```


Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. Skrivskyddad boolean.

**Returnerar:**
boolean - true om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad; annars false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```


Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```


Lägger till ett Paragraph i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph som ska läggas till i slutet av samlingen. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```


Lägger till ett innehåll av ParagraphCollection i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection som ska läggas till i slutet av samlingen. |

**Returnerar:**
int - Indexet där Paragraph har lagts till eller -1 om det inte finns något att lägga till.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```


Bestämmer indexet för ett specifikt objekt i List.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objektet att söka efter i List. |

**Returnerar:**
int - Indexet för item om det hittas i listan; annars -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```


Infogar ett Paragraph i samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Paragraph ska infogas. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph att infoga. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```


Infogar ett innehåll av ParagraphCollection i samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där paragraphs ska infogas. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Paragraphs att infoga. |

### clear() {#clear--}
```
public final void clear()
```


Tar bort alla element från samlingen.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```


Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objektet att söka efter i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om item finns i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```


Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med början vid ett specifikt Array-index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Den endimensionella Array som är destinationen för elementen kopierade från [IGenericCollection](../../com.aspose.slides/igenericcollection). Array måste ha nollbaserad indexering. |
| arrayIndex | int | Det nollbaserade indexet i array där kopieringen börjar. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```


Tar bort den första förekomsten av ett specifikt objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Objektet som ska tas bort från [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om item har tagits bort framgångsrikt från [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false. Denna metod returnerar också false om item inte finns i den ursprungliga [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - En java.util.Iterator för hela samlingen.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returnerar den överordnade slide för en paragraphs-samling. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returnerar den överordnade presentationen för en paragraphs-samling. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```


Lägger till text från angiven HTML-sträng till samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | HTML-text. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Lägger till text från angiven HTML-sträng till samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | HTML-text. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver-återuppringningsobjekt som löser URI:er och hämtar refererade objekt. |
| uri | java.lang.String | URI för att lägga till HTML-dokument. Används för att lösa relativa länkar.

--------------------

Att specificera resolver kan potentiellt introducera en sårbarhet. Använd med försiktighet. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


Konverterar angivna stycken till HTML och returnerar det som ett String-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstParagraphIndex | int | Första styckeindex int |
| paragraphsCount | int | Antal stycken int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Konverteringsalternativ [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Returnerar:**
java.lang.String - Genererad HTML.