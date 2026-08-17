---
title: IParagraphCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Sammlung von Absätzen dar.
type: docs
url: /de/com.aspose.slides/iparagraphcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Stellt eine Sammlung von Absätzen dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Liefert das Element am angegebenen Index. |
| [getCount()](#getCount--) | Liefert die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Fügt ein Paragraph am Ende der Sammlung hinzu. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Fügt den Inhalt einer ParagraphCollection am Ende der Sammlung hinzu. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Fügt ein Paragraph an der angegebenen Position in die Sammlung ein. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Fügt den Inhalt einer ParagraphCollection an der angegebenen Position in die Sammlung ein. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element an dem angegebenen Index aus der Sammlung. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Entfernt das erste Vorkommen eines bestimmten Paragraphen. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Fügt Text aus einer angegebenen HTML-Zeichenkette zur Sammlung hinzu. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Fügt Text aus einer angegebenen HTML-Zeichenkette zur Sammlung hinzu. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Konvertiert die angegebenen Absätze in HTML und gibt sie als String-Objekt zurück. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Liefert das Element am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Liefert die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur lesbare int.

**Rückgabe:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Fügt ein Paragraph am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Das Paragraph, das am Ende der Sammlung hinzugefügt werden soll. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Fügt den Inhalt einer ParagraphCollection am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Die ParagraphCollection, die am Ende der Sammlung hinzugefügt werden soll. |

**Rückgabe:**
int - Der Index, an dem das Paragraph hinzugefügt wurde, oder -1, falls nichts hinzugefügt werden konnte.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Fügt ein Paragraph an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das Paragraph eingefügt werden soll. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Das Paragraph, das eingefügt werden soll. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Fügt den Inhalt einer ParagraphCollection an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Paragraphen eingefügt werden sollen. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Die Paragraphen, die eingefügt werden sollen. |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Elemente aus der Sammlung.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Element an dem angegebenen Index aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Entfernt das erste Vorkommen eines bestimmten Paragraphen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Der zu entfernende Paragraph aus der Sammlung. |

**Rückgabe:**
boolean - true, wenn das Element erfolgreich entfernt wurde; otherwise, false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Fügt Text aus einer angegebenen HTML-Zeichenkette zur Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | HTML-Text. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Fügt Text aus einer angegebenen HTML-Zeichenkette zur Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | HTML-Text. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver-Callback-Objekt, das URIs auflöst und referenzierte Objekte abruft. |
| uri | java.lang.String | URI zum Hinzufügen des HTML-Dokuments. Wird zum Auflösen relativer Links verwendet.

--------------------

Die Angabe eines Resolvers kann potenziell eine Sicherheitslücke einführen. Mit Vorsicht verwenden. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Konvertiert die angegebenen Absätze in HTML und gibt sie als String-Objekt zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstParagraphIndex | int | Erster Absatz-Index |
| paragraphsCount | int | Anzahl der Absätze |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Konvertierungsoptionen [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Rückgabe:**
java.lang.String - Generiertes HTML.