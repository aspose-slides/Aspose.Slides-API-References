---
title: ICommentCollection
second_title: Aspose.Slides Java API-referencia
description: Egy szerző megjegyzéseinek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/icommentcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Egy szerző megjegyzéseinek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Új kommentet ad a gyűjtemény végéhez. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Új modern kommentet ad a gyűjtemény végéhez. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Új kommentet szúr be a gyűjteménybe a megadott indexnél. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Új modern kommentet szúr be a gyűjteménybe a megadott indexnél. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt minden kommenttel. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt a megadott tartomány kommentjeivel. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Eltávolítja a megadott komment első előfordulását a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes kommentjét. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak olvasható [IComment](../../com.aspose.slides/icomment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Új kommentet ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Az új komment egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia a prezentációban, ahová az új kommentet hozzá kell adni. |
| position | java.awt.geom.Point2D.Float | Pozíció a dián, ahová az új kommentet hozzá kell adni. |
| creationTime | java.util.Date | A komment létrehozásának időpontja. |

**Visszatérési érték:**
[IComment](../../com.aspose.slides/icomment) - Hozzáadott komment.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Új modern kommentet ad a gyűjtemény végéhez.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Az új modern komment egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia a prezentációban, ahová az új modern kommentet hozzá kell adni. |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat a dián, amelyhez az új modern komment társul. |
| position | java.awt.geom.Point2D.Float | Pozíció a dián, ahová az új modern kommentet hozzá kell adni. |
| creationTime | java.util.Date | A modern komment létrehozásának időpontja. |

**Visszatérési érték:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Hozzáadott modern komment.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Új kommentet szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe a gyűjteményben, ahol a kommentet be kell szúrni. |
| text | java.lang.String | Az új komment egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia a prezentációban, ahová az új kommentet hozzá kell adni. |
| position | java.awt.geom.Point2D.Float | Pozíció a dián, ahová az új kommentet hozzá kell adni. |
| creationTime | java.util.Date | A komment létrehozásának időpontja. |

**Visszatérési érték:**
[IComment](../../com.aspose.slides/icomment) - Beszúrt komment.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Új modern kommentet szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe a gyűjteményben, ahol a modern kommentet be kell szúrni. |
| text | java.lang.String | Az új modern komment egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia a prezentációban, ahová az új modern kommentet hozzá kell adni. |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat a dián, amelyhez az új modern komment társul. |
| position | java.awt.geom.Point2D.Float | Pozíció a dián, ahová az új modern kommentet hozzá kell adni. |
| creationTime | java.util.Date | A modern komment létrehozásának időpontja. |

**Visszatérési érték:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Beszúrt modern komment.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Létrehoz és visszaad egy tömböt minden kommenttel.

**Visszatérési érték:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) tömbje.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt a megadott tartomány kommentjeivel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első visszaadandó komment indexe. |
| count | int | A visszaadandó kommentek száma. |

**Visszatérési érték:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) tömbje.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a megadott indexű elemet a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nulla-alapú indexe. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Eltávolítja a megadott komment első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Az eltávolítandó komment a gyűjteményből. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja a gyűjtemény összes kommentjét.