---
title: ICommentCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy szerző hozzászólásainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/icommentcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Egy szerző hozzászólásainak gyűjteményét képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az elemet a megadott indexen. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Új hozzászólást ad a gyűjtemény végéhez. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Új modern hozzászólást ad a gyűjtemény végéhez. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Új hozzászólást szúr be a gyűjteménybe a megadott indexen. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Új modern hozzászólást szúr be a gyűjteménybe a megadott indexen. |
| [toArray()](#toArray--) | Létrehozza és visszaad egy tömböt az összes hozzászólással. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehozza és visszaad egy tömböt a megadott tartományból származó összes hozzászólással. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az elemet a megadott indexen a gyűjteményből. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Eltávolítja a megadott hozzászólás első előfordulását a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes hozzászólást a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Visszaadja az elemet a megadott indexen. Csak olvasható [IComment](../../com.aspose.slides/icomment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Új hozzászólást ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Új hozzászólás egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new comment. |
| position | android.graphics.PointF | Pozíció a dián, ahol az új hozzászólást hozzáadni kell. |
| creationTime | java.util.Date | A hozzászólás létrehozásának ideje. |

**Visszatérési érték:**
[IComment](../../com.aspose.slides/icomment) - Hozzáadott hozzászólás.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Új modern hozzászólást ad a gyűjtemény végéhez.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Új modern hozzászólás egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat a dián, amelyhez egy új modern hozzászólás társul. |
| position | android.graphics.PointF | Pozíció a dián, ahol egy új modern hozzászólást hozzáadni kell. |
| creationTime | java.util.Date | A modern hozzászólás létrehozásának ideje. |

**Visszatérési érték:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Hozzáadott modern hozzászólás.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Új hozzászólást szúr be a gyűjteménybe a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A gyűjteményben a beillesztendő hozzászólás elemének indexe. |
| text | java.lang.String | Új hozzászólás egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new comment. |
| position | android.graphics.PointF | Pozíció a dián, ahol az új hozzászólást hozzáadni kell. |
| creationTime | java.util.Date | A hozzászólás létrehozásának ideje. |

**Visszatérési érték:**
[IComment](../../com.aspose.slides/icomment) - Beszúrt hozzászólás.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Új modern hozzászólást szúr be a gyűjteménybe a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A gyűjteményben a beillesztendő modern hozzászólás elemének indexe. |
| text | java.lang.String | Új modern hozzászólás egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat a dián, amelyhez egy új modern hozzászólás társul. |
| position | android.graphics.PointF | Pozíció a dián, ahol egy új modern hozzászólást hozzáadni kell. |
| creationTime | java.util.Date | A modern hozzászólás létrehozásának ideje. |

**Visszatérési érték:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Beszúrt modern hozzászólás.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Létrehozza és visszaadja az összes hozzászólást tartalmazó tömböt.

**Visszatérési érték:**
com.aspose.slides.IComment[] - A [IComment](../../com.aspose.slides/icomment) tömbje.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Létrehozza és visszaadja a megadott tartományból származó összes hozzászólást tartalmazó tömböt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első visszaadandó hozzászólás indexe. |
| count | int | A visszaadandó hozzászólások száma. |

**Visszatérési érték:**
com.aspose.slides.IComment[] - A [IComment](../../com.aspose.slides/icomment) tömbje.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja az elemet a megadott indexen a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nulláral induló indexe. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Eltávolítja a megadott hozzászólás első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | A gyűjteményből eltávolítandó hozzászólás. |
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes hozzászólást a gyűjteményből.