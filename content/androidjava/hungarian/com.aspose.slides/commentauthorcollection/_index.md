---
title: CommentAuthorCollection
second_title: Aspose.Slides Android számára Java API Referencia
description: A megjegyzés szerzők gyűjteményét reprezentálja.
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

A megjegyzés szerzők gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Lekéri a gyűjteményben ténylegesen található elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Új szerzőt ad a gyűjtemény végéhez. |
| [toArray()](#toArray--) | Létrehoz és visszaad egy tömböt az összes szerzővel. |
| [findByName(String name)](#findByName-java.lang.String-) | Megkeresi a szerzőt a gyűjteményben név alapján. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Megkeresi a szerzőt a gyűjteményben név és monogram alapján. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a szerzőt a gyűjtemény megadott indexén. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Eltávolítja a megadott szerző első előfordulását a gyűjteményben. |
| [clear()](#clear--) | Eltávolítja az összes szerzőt a gyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
### size() {#size--}
```
public final int size()
```

Lekéri a gyűjteményben ténylegesen található elemek számát. Csak olvasható int.

**Visszaad:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

Lekéri a megadott indexű elemet. Csak olvasható [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszaad:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

Új szerzőt ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az új szerző neve. |
| initials | java.lang.String | Az új szerző monogramja. |

**Visszaad:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Új [ICommentAuthor](../../com.aspose.slides/icommentauthor) objektum.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Létrehoz és visszaad egy tömböt az összes szerzővel.

**Visszaad:**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) tömb
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Megkeresi a szerzőt a gyűjteményben név alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresendő szerző neve. |

**Visszaad:**
com.aspose.slides.ICommentAuthor[] - Szerző vagy null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Megkeresi a szerzőt a gyűjteményben név és monogram alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresendő szerző neve. |
| initials | java.lang.String | A keresendő szerző monogramja. |

**Visszaad:**
com.aspose.slides.ICommentAuthor[] - Szerző vagy null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a szerzőt a gyűjtemény megadott indexén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nulla-alapú indexe. |
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

Eltávolítja az összes szerzőt a gyűjteményből.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Visszaad egy felsorolót, amely végigiterál a gyűjteményen.

**Visszaad:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszaad:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Egy java.util.Iterator a teljes gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kiinduló index a cél tömbben. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszaad:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszaad:**
java.lang.Object