---
title: CommentCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Sammlung von Kommentaren eines Autors dar.
type: docs
url: /de/com.aspose.slides/commentcollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Stellt eine Sammlung von Kommentaren eines Autors dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [get_Item(int index)](#get-Item-int-) | Ermittelt das Element am angegebenen Index. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Fügt einen neuen Kommentar am Ende einer Sammlung hinzu. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Fügt einen neuen modernen Kommentar am Ende einer Sammlung hinzu. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Fügt einen neuen Kommentar in eine Sammlung an dem angegebenen Index ein. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Fügt einen neuen modernen Kommentar in eine Sammlung an dem angegebenen Index ein. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array mit allen Kommentaren zurück. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array mit allen Kommentaren aus dem angegebenen Bereich zurück. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index in einer Sammlung. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Entfernt das erste Vorkommen des angegebenen Kommentars in einer Sammlung. |
| [clear()](#clear--) | Entfernt alle Kommentare aus einer Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Findet einen Kommentar in der Sammlung anhand des Index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisationsobjekt zurück. |
### size() {#size--}
```
public final int size()
```


Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur lesend  int .

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```


Ermittelt das Element am angegebenen Index. Nur lesend [Comment](../../com.aspose.slides/comment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Fügt einen neuen Kommentar am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Einfacher Text eines neuen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer Kommentar hinzugefügt werden soll. |
| position | java.awt.geom.Point2D.Float | Position auf einer Folie, an der ein neuer Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Kommentar-Erstellung. |

**Rückgabe:**
[IComment](../../com.aspose.slides/icomment) - Hinzugefügter Kommentar.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Fügt einen neuen modernen Kommentar am Ende einer Sammlung hinzu.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Einfacher Text eines neuen modernen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer moderner Kommentar hinzugefügt werden soll. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form auf einer Folie, mit der ein neuer moderner Kommentar verknüpft ist. |
| position | java.awt.geom.Point2D.Float | Position auf einer Folie, an der ein neuer moderner Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Erstellung eines modernen Kommentars. |

**Rückgabe:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Hinzugefügter moderner Kommentar.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Fügt einen neuen Kommentar in eine Sammlung an dem angegebenen Index ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements in einer Sammlung, an dem der Kommentar eingefügt werden soll. |
| text | java.lang.String | Einfacher Text eines neuen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer Kommentar hinzugefügt werden soll. |
| position | java.awt.geom.Point2D.Float | Position auf einer Folie, an der ein neuer Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Kommentar-Erstellung. |

**Rückgabe:**
[IComment](../../com.aspose.slides/icomment) - Eingefügter Kommentar.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Fügt einen neuen modernen Kommentar in eine Sammlung an dem angegebenen Index ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements in einer Sammlung, an dem ein moderner Kommentar eingefügt werden soll. |
| text | java.lang.String | Einfacher Text eines neuen modernen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer moderner Kommentar hinzugefügt werden soll. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form auf einer Folie, mit der ein neuer moderner Kommentar verknüpft ist. |
| position | java.awt.geom.Point2D.Float | Position auf einer Folie, an der ein neuer moderner Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Erstellung eines modernen Kommentars. |

**Rückgabe:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Eingefügter moderner Kommentar.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```


Erstellt und gibt ein Array mit allen Kommentaren zurück.

**Rückgabe:**
com.aspose.slides.IComment[] - Array von [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```


Erstellt und gibt ein Array mit allen Kommentaren aus dem angegebenen Bereich zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Ein Index des ersten zurückzugebenden Kommentars. |
| count | int | Anzahl der zurückzugebenden Kommentare. |

**Rückgabe:**
com.aspose.slides.IComment[] - Array von [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt das Element am angegebenen Index in einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```


Entfernt das erste Vorkommen des angegebenen Kommentars in einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Der zu entfernende Kommentar aus einer Sammlung. |
### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Kommentare aus einer Sammlung.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Ein java.util.Iterator für die gesamte Sammlung.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```


Findet einen Kommentar in der Sammlung anhand des Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| idx | int | Eindeutiger Index eines zu findenden Kommentars  int . |

**Rückgabe:**
[IComment](../../com.aspose.slides/icomment) - Gefundener Kommentar oder null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente aus der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur lesend  boolean .

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt ein Synchronisationsobjekt zurück. Nur lesend  Object .

**Rückgabe:**
java.lang.Object