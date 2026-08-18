---
title: CommentAuthorCollection
second_title: Aspose.Slides Java API referencia
description: Egy megjegyzés szerzők gyűjteményét képvisel.
type: docs
url: /hu/com.aspose.slides/commentauthorcollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Egy megjegyzés szerzők gyűjteményét képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Új szerzőt ad hozzá a gyűjtemény végéhez. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt minden szerzővel. |
| [findByName(String name)](#findByName-java.lang.String-) | Megkeresi a szerzőt a gyűjteményben név alapján. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Megkeresi a szerzőt a gyűjteményben név és kezdőbetűk alapján. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a szerzőt a gyűjtemény meghatározott indexén. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Eltávolítja a megadott szerző első előfordulását a gyűjteményben. |
| [clear()](#clear--) | Eltávolítja az összes szerzőt egy gyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

Visszaadja a megadott indexű elemet. Csak olvasható [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

Új szerzőt ad hozzá a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az új szerző neve. |
| initials | java.lang.String | Az új szerző kezdőbetűi. |

**Visszatér:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Új [ICommentAuthor](../../com.aspose.slides/icommentauthor) objektum.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Létrehoz és visszaad egy tömböt minden szerzővel.

**Visszatér:**
com.aspose.slides.ICommentAuthor[] - Tömb a(z) [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Megkeresi a szerzőt a gyűjteményben név alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A megtalálandó szerző neve. |

**Visszatér:**
com.aspose.slides.ICommentAuthor[] - Szerző vagy null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Megkeresi a szerzőt a gyűjteményben név és kezdőbetűk alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A megtalálandó szerző neve. |
| initials | java.lang.String | A megtalálandó szerző kezdőbetűi. |

**Visszatér:**
com.aspose.slides.ICommentAuthor[] - Szerző vagy null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a szerzőt a gyűjtemény meghatározott indexén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nullától számított indexe. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Eltávolítja a megadott szerző első előfordulását a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Az eltávolítandó szerző a gyűjteményből. |
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes szerzőt egy gyűjteményből.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Visszaad egy enumerátort, amely bejárja a gyűjteményt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Ez egy IGenericEnumerator, amely a gyűjtemény bejárására használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Ez egy java.util.Iterator a teljes gyűjteményhez.
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

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatér:**
java.lang.Object