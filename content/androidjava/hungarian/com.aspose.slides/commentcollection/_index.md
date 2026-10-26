---
title: CommentCollection
second_title: Aspose.Slides for Android Java API referencia
description: Egy szerző megjegyzéseinek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/commentcollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Egy szerző megjegyzéseinek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | A gyűjteményben ténylegesen található elemek számát adja vissza. |
| [get_Item(int index)](#get-Item-int-) | A megadott indexnél található elemet adja vissza. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Új megjegyzést ad a gyűjtemény végéhez. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Új modern megjegyzést ad a gyűjtemény végéhez. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Új megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Új modern megjegyzést szúr be a gyűjteménybe a megadott indexnél. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt az összes megjegyzéssel. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Létrehoz és visszaad egy tömböt a megadott tartományba eső összes megjegyzéssel. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexnél lévő elemet a gyűjteményből. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Eltávolítja a megadott megjegyzés első előfordulását a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes megjegyzést a gyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Megtalál egy megjegyzést a gyűjteményben index alapján. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja az összes elemet a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |
### size() {#size--}
```
public final int size()
```

A gyűjteményben ténylegesen található elemek számát adja vissza. Csak olvasható  int .

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

A megadott indexnél található elemet adja vissza. Csak olvasható [Comment](../../com.aspose.slides/comment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Új megjegyzést ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Az új megjegyzés egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia a bemutatóban, ahová az új megjegyzést fel kell venni. |
| position | android.graphics.PointF | Pozíció a dián, ahová az új megjegyzést fel kell venni. |
| creationTime | java.util.Date | A megjegyzés létrehozásának időpontja. |

**Visszatér:**
[IComment](../../com.aspose.slides/icomment) - Hozzáadott megjegyzés.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Új modern megjegyzést ad a gyűjtemény végéhez.

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
| text | java.lang.String | Az új modern megjegyzés egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia a bemutatóban, ahová az új modern megjegyzést fel kell venni. |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat a dián, amelyhez az új modern megjegyzés kapcsolódik. |
| position | android.graphics.PointF | Pozíció a dián, ahová az új modern megjegyzést fel kell venni. |
| creationTime | java.util.Date | A modern megjegyzés létrehozásának időpontja. |

**Visszatér:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Hozzáadott modern megjegyzés.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Új megjegyzést szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe a gyűjteményben, ahová a megjegyzést be kell szúrni. |
| text | java.lang.String | Az új megjegyzés egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia a bemutatóban, ahová az új megjegyzést fel kell venni. |
| position | android.graphics.PointF | Pozíció a dián, ahová az új megjegyzést fel kell venni. |
| creationTime | java.util.Date | A megjegyzés létrehozásának időpontja. |

**Visszatér:**
[IComment](../../com.aspose.slides/icomment) - Beszúrt megjegyzés.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Új modern megjegyzést szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe a gyűjteményben, ahová a modern megjegyzést be kell szúrni. |
| text | java.lang.String | Az új modern megjegyzés egyszerű szövege. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia a bemutatóban, ahová az új modern megjegyzést fel kell venni. |
| shape | [IShape](../../com.aspose.slides/ishape) | Alakzat a dián, amelyhez az új modern megjegyzés kapcsolódik. |
| position | android.graphics.PointF | Pozíció a dián, ahová az új modern megjegyzést fel kell venni. |
| creationTime | java.util.Date | A modern megjegyzés létrehozásának időpontja. |

**Visszatér:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Beszúrt modern megjegyzés.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Létrehoz és visszaad egy tömböt az összes megjegyzéssel.

**Visszatér:**
com.aspose.slides.IComment[] - Tömb a [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Létrehoz és visszaad egy tömböt a megadott tartományba eső összes megjegyzéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | int | Az első visszaadandó megjegyzés indexe. |
| count | int | A visszaadandó megjegyzések száma. |

**Visszatér:**
com.aspose.slides.IComment[] - Tömb a [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a megadott indexnél lévő elemet a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nullától kezdődő indexe. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Eltávolítja a megadott megjegyzés első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | A gyűjteményből eltávolítandó megjegyzés. |
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes megjegyzést a gyűjteményből.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Egy IGenericEnumerator, amelyet a gyűjteményen való iteráláshoz lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Egy java.util.Iterator a teljes gyűjteményhez.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Megkeres egy megjegyzést a gyűjteményben index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| idx | int | Egy megjegyzés egyedi indexe a kereséshez  int . |

**Visszatér:**
[IComment](../../com.aspose.slides/icomment) - Megtalált megjegyzés vagy null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja az összes elemet a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható  boolean .

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható  Object .

**Visszatér:**
java.lang.Object