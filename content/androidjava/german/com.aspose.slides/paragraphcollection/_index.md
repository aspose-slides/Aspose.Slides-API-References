---
title: ParagraphCollection
second_title: Aspose.Slides für Android mittels Java-API-Referenz
description: Stellt eine Sammlung von Absätzen dar.
type: docs
url: /de/com.aspose.slides/paragraphcollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Stellt eine Sammlung von Absätzen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [isReadOnly()](#isReadOnly--) | Ermittelt einen Wert, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. |
| [get_Item(int index)](#get-Item-int-) | Ermittelt das Element am angegebenen Index. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Fügt ein Paragraph-Objekt am Ende der Sammlung hinzu. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Fügt den Inhalt einer ParagraphCollection am Ende der Sammlung hinzu. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Bestimmt den Index eines bestimmten Elements in der Liste. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Fügt ein Paragraph-Objekt an dem angegebenen Index in die Sammlung ein. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Fügt den Inhalt einer ParagraphCollection an dem angegebenen Index in die Sammlung ein. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index aus der Sammlung. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Entfernt das erste Auftreten eines bestimmten Objekts aus [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie einer Absatzsammlung zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation einer Absatzsammlung zurück. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Fügt der Sammlung Text aus einer angegebenen HTML-Zeichenkette hinzu. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Fügt der Sammlung Text aus einer angegebenen HTML-Zeichenkette hinzu. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Konvertiert die angegebenen Absätze in HTML und gibt das Ergebnis als String-Objekt zurück. |

### getCount() {#getCount--}
```
public final int getCount()
```

Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur lesbar int.

**Rückgabewert:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ermittelt einen Wert, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. Nur lesbar boolean.

**Rückgabewert:**
boolean – true, wenn [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist; andernfalls false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Ermittelt das Element am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Fügt ein Paragraph-Objekt am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Der Paragraph, der am Ende der Sammlung hinzugefügt werden soll. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Fügt den Inhalt einer ParagraphCollection am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Die ParagraphCollection, die am Ende der Sammlung hinzugefügt werden soll. |

**Rückgabewert:**
int – Der Index, an dem der Paragraph hinzugefügt wurde, oder -1, wenn nichts hinzuzufügen war.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Bestimmt den Index eines bestimmten Elements in der Liste.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Das Objekt, das in der Liste gesucht werden soll. |

**Rückgabewert:**
int – Der Index des Elements, falls im List gefunden; andernfalls -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Fügt ein Paragraph-Objekt an dem angegebenen Index in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem Paragraph eingefügt werden soll. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Der Paragraph, der eingefügt werden soll. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Fügt den Inhalt einer ParagraphCollection an dem angegebenen Index in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem Absätze eingefügt werden sollen. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Die Absätze, die eingefügt werden sollen. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus der Sammlung.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Das Objekt, das in [IGenericCollection](../../com.aspose.slides/igenericcollection) gesucht werden soll. |

**Rückgabewert:**
boolean – true, wenn das Element in [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wurde; andernfalls false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Das eindimensionale Array, das Ziel der aus [IGenericCollection](../../com.aspose.slides/igenericcollection) kopierten Elemente ist. Das Array muss nullbasiert sein. |
| arrayIndex | int | Der nullbasierte Index im Array, an dem das Kopieren beginnt. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Entfernt das erste Auftreten eines bestimmten Objekts aus [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Das Objekt, das aus [IGenericCollection](../../com.aspose.slides/igenericcollection) entfernt werden soll. |

**Rückgabewert:**
boolean – true, wenn das Element erfolgreich aus [IGenericCollection](../../com.aspose.slides/igenericcollection) entfernt wurde; andernfalls false. Diese Methode liefert ebenfalls false zurück, wenn das Element im ursprünglichen [IGenericCollection](../../com.aspose.slides/igenericcollection) nicht gefunden wird.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> – Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> – Ein java.util.Iterator für die gesamte Sammlung.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie einer Absatzsammlung zurück. Nur lesbar [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabewert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation einer Absatzsammlung zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Fügt der Sammlung Text aus einer angegebenen HTML-Zeichenkette hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | HTML-Text. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Fügt der Sammlung Text aus einer angegebenen HTML-Zeichenkette hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | HTML-Text. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver-Callback-Objekt, das URIs auflöst und referenzierte Objekte abruft. |
| uri | java.lang.String | URI zum Hinzufügen des HTML-Dokuments. Wird zum Auflösen relativer Links verwendet. |

--------------------
Das Angeben eines Resolvers kann potenziell eine Sicherheitslücke einführen. Mit Vorsicht verwenden.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Konvertiert die angegebenen Absätze in HTML und gibt das Ergebnis als String-Objekt zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstParagraphIndex | int | Index des ersten Absatzes |
| paragraphsCount | int | Anzahl der Absätze |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Umwandlungsoptionen [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Rückgabewert:**
java.lang.String – erzeugtes HTML.