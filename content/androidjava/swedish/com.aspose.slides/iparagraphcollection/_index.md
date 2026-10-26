---
title: IParagraphCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av stycken.
type: docs
url: /sv/com.aspose.slides/iparagraphcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Representerar en samling av stycken.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Lägger till ett Paragraph i slutet av samlingen. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Lägger till innehållet från ParagraphCollection i slutet av samlingen. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Infogar ett Paragraph i samlingen på det angivna indexet. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Infogar innehållet från ParagraphCollection i samlingen på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Tar bort den första förekomsten av ett specifikt stycke. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Lägger till text från angiven html-sträng till samlingen. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Lägger till text från angiven html-sträng till samlingen. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Konverterar angivna stycken till HTML och returnerar det som ett String-objekt. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Hämtar antalet element som faktiskt finns i samlingen. Endast läsning int.

**Returnerar:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Lägger till ett Paragraph i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph som ska läggas till i slutet av samlingen. |
### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Lägger till innehållet från ParagraphCollection i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection som ska läggas till i slutet av samlingen. |

**Returnerar:**
int - Indexet där Paragraph har lagts till eller -1 om det inte finns något att lägga till.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Infogar ett Paragraph i samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Paragraph ska infogas. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph som ska infogas. |
### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Infogar innehållet från ParagraphCollection i samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där stycken ska infogas. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Stycken som ska infogas. |
### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla element från samlingen.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |
### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Tar bort den första förekomsten av ett specifikt stycke.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Stycket som ska tas bort från samlingen. |

**Returnerar:**
boolean - true om objektet togs bort; annars false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Lägger till text från angiven html-sträng till samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | HTML-text. |
### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Lägger till text från angiven html-sträng till samlingen.

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
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Konverterar angivna stycken till HTML och returnerar det som ett String-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstParagraphIndex | int | Första styckets index int |
| paragraphsCount | int | Antal stycken int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Konverteringsalternativ [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Returnerar:**
java.lang.String - Genererad HTML.