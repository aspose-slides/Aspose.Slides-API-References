---
title: CommentCollection
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [size()](#size--) | Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Fügt am Ende einer Sammlung einen neuen Kommentar hinzu. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Fügt am Ende einer Sammlung einen neuen modernen Kommentar hinzu. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Fügt einen neuen Kommentar an der angegebenen Position in die Sammlung ein. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Fügt einen neuen modernen Kommentar an der angegebenen Position in die Sammlung ein. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array mit allen Kommentaren zurück. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array mit allen Kommentaren aus dem angegebenen Bereich zurück. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index aus einer Sammlung. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Entfernt das erste Vorkommen des angegebenen Kommentars aus einer Sammlung. |
| [clear()](#clear--) | Entfernt alle Kommentare aus einer Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Findet einen Kommentar in der Sammlung anhand des Index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |

### size() {#size--}
```
public final int size()
```

Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. Nur lesend  int .

**Rückgabe:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Gibt das Element am angegebenen Index zurück. Nur lesend [Comment](../../com.aspose.slides/comment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Fügt am Ende einer Sammlung einen neuen Kommentar hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Klartext des neuen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer Kommentar hinzugefügt werden soll. |
| position | android.graphics.PointF | Position auf einer Folie, an der ein neuer Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Kommentarerstellung. |

**Rückgabe:**
[IComment](../../com.aspose.slides/icomment) - Hinzugefügter Kommentar.

### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Fügt am Ende einer Sammlung einen neuen modernen Kommentar hinzu.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Klartext des neuen modernen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer moderner Kommentar hinzugefügt werden soll. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form auf einer Folie, der ein neuer moderner Kommentar zugeordnet ist. |
| position | android.graphics.PointF | Position auf einer Folie, an der ein neuer moderner Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Erstellung eines modernen Kommentars. |

**Rückgabe:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Hinzugefügter moderner Kommentar.

### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Fügt einen neuen Kommentar an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements in einer Sammlung, an dem der Kommentar eingefügt werden soll. |
| text | java.lang.String | Klartext des neuen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer Kommentar hinzugefügt werden soll. |
| position | android.graphics.PointF | Position auf einer Folie, an der ein neuer Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Kommentarerstellung. |

**Rückgabe:**
[IComment](../../com.aspose.slides/icomment) - Eingefügter Kommentar.

### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Fügt einen neuen modernen Kommentar an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements in einer Sammlung, an dem ein moderner Kommentar eingefügt werden soll. |
| text | java.lang.String | Klartext des neuen modernen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer moderner Kommentar hinzugefügt werden soll. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form auf einer Folie, der ein neuer moderner Kommentar zugeordnet ist. |
| position | android.graphics.PointF | Position auf einer Folie, an der ein neuer moderner Kommentar hinzugefügt werden soll. |
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
| startIndex | int | Index des ersten zurückzugebenden Kommentars. |
| count | int | Anzahl der zurückzugebenden Kommentare. |

**Rückgabe:**
com.aspose.slides.IComment[] - Array von [Comment](../../com.aspose.slides/comment).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Entfernt das erste Vorkommen des angegebenen Kommentars aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Der Kommentar, der aus einer Sammlung entfernt werden soll. |

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

Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. Nur lesend  boolean .

**Rückgabe:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt eine Synchronisationswurzel zurück. Nur lesend  Object .

**Rückgabe:**
java.lang.Object