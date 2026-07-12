---
title: ICommentCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Kommentaren eines Autors dar.
type: docs
url: /de/com.aspose.slides/icommentcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Stellt eine Sammlung von Kommentaren eines Autors dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Fügt einen neuen Kommentar am Ende einer Sammlung hinzu. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Fügt einen neuen modernen Kommentar am Ende einer Sammlung hinzu. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Fügt einen neuen Kommentar in einer Sammlung am angegebenen Index ein. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Fügt einen neuen modernen Kommentar in einer Sammlung am angegebenen Index ein. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array mit allen Kommentaren zurück. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array mit allen Kommentaren aus dem angegebenen Bereich zurück. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index in einer Sammlung. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Entfernt das erste Vorkommen des angegebenen Kommentars in einer Sammlung. |
| [clear()](#clear--) | Entfernt alle Kommentare aus einer Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Ruft das Element am angegebenen Index ab. Nur lesbar [IComment](../../com.aspose.slides/icomment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Fügt einen neuen Kommentar am Ende einer Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Klartext des neuen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer Kommentar hinzugefügt werden soll. |
| position | android.graphics.PointF | Position auf einer Folie, wo ein neuer Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Kommentar-Erstellung. |

**Rückgabewert:**
[IComment](../../com.aspose.slides/icomment) - Hinzugefügter Kommentar.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Fügt einen neuen modernen Kommentar am Ende einer Sammlung hinzu.

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
| position | android.graphics.PointF | Position auf einer Folie, wo ein neuer moderner Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Erstellung des modernen Kommentars. |

**Rückgabewert:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Hinzugefügter moderner Kommentar.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Fügt einen neuen Kommentar in einer Sammlung am angegebenen Index ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements in einer Sammlung, an dem der Kommentar eingefügt werden soll. |
| text | java.lang.String | Klartext des neuen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer Kommentar hinzugefügt werden soll. |
| position | android.graphics.PointF | Position auf einer Folie, wo ein neuer Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Kommentar-Erstellung. |

**Rückgabewert:**
[IComment](../../com.aspose.slides/icomment) - Eingefügter Kommentar.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Fügt einen neuen modernen Kommentar in einer Sammlung am angegebenen Index ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements in einer Sammlung, an dem ein moderner Kommentar eingefügt werden soll. |
| text | java.lang.String | Klartext des neuen modernen Kommentars. |
| slide | [ISlide](../../com.aspose.slides/islide) | Folie in einer Präsentation, zu der ein neuer moderner Kommentar hinzugefügt werden soll. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form auf einer Folie, der ein neuer moderner Kommentar zugeordnet ist. |
| position | android.graphics.PointF | Position auf einer Folie, wo ein neuer moderner Kommentar hinzugefügt werden soll. |
| creationTime | java.util.Date | Zeitpunkt der Erstellung des modernen Kommentars. |

**Rückgabewert:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Eingefügter moderner Kommentar.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Erstellt und gibt ein Array mit allen Kommentaren zurück.

**Rückgabewert:**
com.aspose.slides.IComment[] - Array von [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Erstellt und gibt ein Array mit allen Kommentaren aus dem angegebenen Bereich zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Index des ersten zurückzugebenden Kommentars. |
| count | int | Anzahl der zurückzugebenden Kommentare. |

**Rückgabewert:**
com.aspose.slides.IComment[] - Array von [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt das Element am angegebenen Index in einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Entfernt das erste Vorkommen des angegebenen Kommentars in einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Der aus einer Sammlung zu entfernende Kommentar. |

### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Kommentare aus einer Sammlung.