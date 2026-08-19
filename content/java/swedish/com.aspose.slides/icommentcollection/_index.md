---
title: ICommentCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling kommentarer från en författare.
type: docs
url: /sv/com.aspose.slides/icommentcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Representerar en samling kommentarer från en författare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Lägger till en ny kommentar i slutet av en samling. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Lägger till en ny modern kommentar i slutet av en samling. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Infogar en ny kommentar i en samling på det angivna indexet. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Infogar en ny modern kommentar i en samling på det angivna indexet. |
| [toArray()](#toArray--) | Skapar och returnerar en array med alla kommentarer. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Skapar och returnerar en array med alla kommentarer från det angivna intervallet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i en samling. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Tar bort den första förekomsten av den angivna kommentaren i en samling. |
| [clear()](#clear--) | Tar bort alla kommentarer från en samling. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [IComment](../../com.aspose.slides/icomment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Lägger till en ny kommentar i slutet av en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Vanlig text för en ny kommentar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild i en presentation där en ny kommentar ska läggas till. |
| position | java.awt.geom.Point2D.Float | Position på en bild där en ny kommentar ska läggas till. |
| creationTime | java.util.Date | Tid för skapandet av en kommentar. |

**Returnerar:**
[IComment](../../com.aspose.slides/icomment) - Tillagd kommentar.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Lägger till en ny modern kommentar i slutet av en samling.

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
| slide | [ISlide](../../com.aspose.slides/islide) | Bild i en presentation där en ny modern kommentar ska läggas till. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form på en bild som en ny modern kommentar är kopplad till. |
| position | java.awt.geom.Point2D.Float | Position på en bild där en ny modern kommentar ska läggas till. |
| creationTime | java.util.Date | Tid för skapandet av en modern kommentar. |

**Returnerar:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Tillagd modern kommentar.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Infogar en ny kommentar i en samling på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet i en samling där kommentaren ska infogas. |
| text | java.lang.String | Vanlig text för en ny kommentar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild i en presentation där en ny kommentar ska läggas till. |
| position | java.awt.geom.Point2D.Float | Position på en bild där en ny kommentar ska läggas till. |
| creationTime | java.util.Date | Tid för skapandet av en kommentar. |

**Returnerar:**
[IComment](../../com.aspose.slides/icomment) - Infogad kommentar.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Infogar en ny modern kommentar i en samling på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet i en samling där en modern kommentar ska infogas. |
| text | java.lang.String | Vanlig text för en ny modern kommentar. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild i en presentation där en ny modern kommentar ska läggas till. |
| shape | [IShape](../../com.aspose.slides/ishape) | Form på en bild som en ny modern kommentar är kopplad till. |
| position | java.awt.geom.Point2D.Float | Position på en bild där en ny modern kommentar ska läggas till. |
| creationTime | java.util.Date | Tid för skapandet av en modern kommentar. |

**Returnerar:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Infogad modern kommentar.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Skapar och returnerar en array med alla kommentarer.

**Returnerar:**
com.aspose.slides.IComment[] - Array av [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Skapar och returnerar en array med alla kommentarer från det angivna intervallet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Index för den första kommentaren som ska returneras. |
| count | int | Antal kommentarer som ska returneras. |

**Returnerar:**
com.aspose.slides.IComment[] - Array av [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på det angivna indexet i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index för elementet som ska tas bort. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Tar bort den första förekomsten av den angivna kommentaren i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Kommentaren som ska tas bort från en samling. |

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla kommentarer från en samling.