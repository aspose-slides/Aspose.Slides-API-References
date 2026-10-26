---
title: CommentCollection
second_title: Aspose.Slides for Java API referencia
description: Egy szerző megjegyzéseinek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/commentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Egy szerző megjegyzéseinek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | A gyűjteményben ténylegesen tárolt elemek számát adja vissza. |
| [get_Item(int index)](#get-Item-int-) | A megadott indexnél lévő elemet adja vissza. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Új megjegyzést ad a gyűjtemény végéhez. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Új modern megjegyzést ad a gyűjtemény végéhez. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Új megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Új modern megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [toArray()](#toArray--) | Létrehozza és visszaad egy tömböt az összes megjegyzéssel. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehozza és visszaad egy tömböt a megadott tartományból származó összes megjegyzéssel. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexnél lévő elemet. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Eltávolítja a megadott megjegyzés első előfordulását a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes megjegyzését. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Megkeresi a megjegyzést a gyűjteményben index alapján. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |

### size() {#size--}
```
public final int size()
```

A gyűjteményben ténylegesen tárolt elemek számát adja vissza. **Csak olvasható** int .

**Visszaad:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

A megadott indexnél lévő elemet adja vissza. **Csak olvasható** [Comment](../../com.aspose.slides/comment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszaad:**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Új megjegyzést ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Új megjegyzés egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapozitív a prezentációban, ahová a megjegyzést fel kell venni. |
| position | java.awt.geom.Point2D.Float | Pozíció a dián, ahová a megjegyzést fel kell venni. |
| creationTime | java.util.Date | A megjegyzés létrehozásának időpontja. |

**Visszaad:**
[IComment](../../com.aspose.slides/icomment) – Hozzáadott megjegyzés.

### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Új modern megjegyzést ad a gyűjtemény végéhez.

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
| text | java.lang.String | Új modern megjegyzés egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapozitív a prezentációban, ahová a modern megjegyzést fel kell venni. |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat a dián, amelyhez az új modern megjegyzés kapcsolódik. |
| position | java.awt.geom.Point2D.Float | Pozíció a dián, ahová a modern megjegyzést fel kell venni. |
| creationTime | java.util.Date | A modern megjegyzés létrehozásának időpontja. |

**Visszaad:**
[IModernComment](../../com.aspose.slides/imoderncomment) – Hozzáadott modern megjegyzés.

### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Új megjegyzést szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe a gyűjteményben, ahová a megjegyzést be kell szúrni. |
| text | java.lang.String | Új megjegyzés egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapozitív a prezentációban, ahová a megjegyzést fel kell venni. |
| position | java.awt.geom.Point2D.Float | Pozíció a dián, ahová a megjegyzést fel kell venni. |
| creationTime | java.util.Date | A megjegyzés létrehozásának időpontja. |

**Visszaad:**
[IComment](../../com.aspose.slides/icomment) – Beszúrt megjegyzés.

### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Új modern megjegyzést szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe a gyűjteményben, ahová a modern megjegyzést be kell szúrni. |
| text | java.lang.String | Új modern megjegyzés egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapozitív a prezentációban, ahová a modern megjegyzést fel kell venni. |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat a dián, amelyhez az új modern megjegyzés kapcsolódik. |
| position | java.awt.geom.Point2D.Float | Pozíció a dián, ahová a modern megjegyzést fel kell venni. |
| creationTime | java.util.Date | A modern megjegyzés létrehozásának időpontja. |

**Visszaad:**
[IModernComment](../../com.aspose.slides/imoderncomment) – Beszúrt modern megjegyzés.

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Létrehozza és visszaad egy tömböt az összes megjegyzéssel.

**Visszaad:**
com.aspose.slides.IComment[] – [Comment](../../com.aspose.slides/comment) tömbje.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Létrehozza és visszaad egy tömböt a megadott tartományból származó összes megjegyzéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első visszaadandó megjegyzés indexe. |
| count | int | A visszaadandó megjegyzések száma. |

**Visszaad:**
com.aspose.slides.IComment[] – [Comment](../../com.aspose.slides/comment) tömbje.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a gyűjteményben a megadott indexnél lévő elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem null-alapú indexe. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Eltávolítja a megadott megjegyzés első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Az eltávolítandó megjegyzés. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja a gyűjtemény összes megjegyzését.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszaad:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> – IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszaad:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> – java.util.Iterator a teljes gyűjteményhez.

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Megkeresi a megjegyzést a gyűjteményben index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| idx | int | A keresendő megjegyzés egyedi indexe. |

**Visszaad:**
[IComment](../../com.aspose.slides/icomment) – Talált megjegyzés vagy null [IComment](../../com.aspose.slides/icomment).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. **Csak olvasható** boolean .

**Visszaad:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökérobjektumot. **Csak olvasható** Object .

**Visszaad:**
java.lang.Object