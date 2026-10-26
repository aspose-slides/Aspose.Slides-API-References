---
title: CommentCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling kommentarer från en författare.
type: docs
url: /sv/com.aspose.slides/commentcollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Representerar en samling kommentarer från en författare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Lägger till en ny kommentar i slutet av en samling. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Lägger till en ny modern kommentar i slutet av en samling. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Infogar en ny kommentar i en samling på det angivna indexet. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Infogar en ny modern kommentar i en samling på det angivna indexet. |
| [toArray()](#toArray--) | Skapar och returnerar en matris med alla kommentarer. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Skapar och returnerar en matris med alla kommentarer från det angivna intervallet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i en samling. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Tar bort den första förekomsten av den angivna kommentaren i en samling. |
| [clear()](#clear--) | Tar bort alla kommentarer från en samling. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Hittar en kommentar i samlingen efter index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna matrisen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som anger om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar en synkroniseringsrot. |
### size() {#size--}
```
public final int size()
```


Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad  int .

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```


Hämtar elementet på det angivna indexet. Skrivskyddad [Comment](../../com.aspose.slides/comment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Lägg till en ny kommentar i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Vanlig text för en ny kommentar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild i en presentation där den nya kommentaren ska läggas till. |
| position | java.awt.geom.Point2D.Float | Position på en bild där den nya kommentaren ska läggas till. |
| creationTime | java.util.Date | Tid för kommentarskapande. |

**Returnerar:**
[IComment](../../com.aspose.slides/icomment) - Tillagd kommentar.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Lägg till en ny modern kommentar i slutet av en samling.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Vanlig text för en ny modern kommentar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild i en presentation där den nya moderna kommentaren ska läggas till. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form på en bild som den nya moderna kommentaren är associerad med. |
| position | java.awt.geom.Point2D.Float | Position på en bild där den nya moderna kommentaren ska läggas till. |
| creationTime | java.util.Date | Tid för en modern kommentarskapande. |

**Returnerar:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Tillagd modern kommentar.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Infoga en ny kommentar i en samling på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet i en samling där kommentaren ska infogas. |
| text | java.lang.String | Vanlig text för en ny kommentar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild i en presentation där den nya kommentaren ska läggas till. |
| position | java.awt.geom.Point2D.Float | Position på en bild där den nya kommentaren ska läggas till. |
| creationTime | java.util.Date | Tid för kommentarskapande. |

**Returnerar:**
[IComment](../../com.aspose.slides/icomment) - Infogad kommentar.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Infoga en ny modern kommentar i en samling på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet i en samling där modern kommentar ska infogas. |
| text | java.lang.String | Vanlig text för en ny modern kommentar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild i en presentation där den nya moderna kommentaren ska läggas till. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form på en bild som en ny modern kommentar är associerad med. |
| position | java.awt.geom.Point2D.Float | Position på en bild där den nya moderna kommentaren ska läggas till. |
| creationTime | java.util.Date | Tid för en modern kommentarskapande. |

**Returnerar:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Infogad modern kommentar.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```


Skapar och returnerar en matris med alla kommentarer.

**Returnerar:**
com.aspose.slides.IComment[] - Matris av [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```


Skapar och returnerar en matris med alla kommentarer från det angivna intervallet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Ett index för den första kommentaren att returnera. |
| count | int | Antalet kommentarer att returnera. |

**Returnerar:**
com.aspose.slides.IComment[] - Matris av [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort elementet på det angivna indexet i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```


Tar bort den första förekomsten av den angivna kommentaren i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Kommentaren som ska tas bort från en samling. |

### clear() {#clear--}
```
public final void clear()
```


Tar bort alla kommentarer från en samling.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - En java.util.Iterator för hela samlingen.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```


Hittar en kommentar i samlingen efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| idx | int | Unikt index för en kommentar att hitta  int . |

**Returnerar:**
[IComment](../../com.aspose.slides/icomment) - Hittad kommentar eller null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopierar alla element från samlingen till den angivna matrisen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målmatsris. |
| index | int | Startindex i målmatsrisen. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returnerar ett värde som anger om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad  boolean .

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returnerar en synkroniseringsrot. Skrivskyddad  Object .

**Returnerar:**
java.lang.Object