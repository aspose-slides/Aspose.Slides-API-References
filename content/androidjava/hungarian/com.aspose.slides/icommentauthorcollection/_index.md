---
title: ICommentAuthorCollection
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: A megjegyzés szerzők gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/icommentauthorcollection/
---
**Az összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Egy megjegyzés szerzők gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexnél. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Új szerzőt ad hozzá a gyűjtemény végéhez. |
| [toArray()](#toArray--) | Létrehozza és visszaad egy tömböt az összes szerzővel. |
| [findByName(String name)](#findByName-java.lang.String-) | Megkeresi a szerzőt a gyűjteményben név alapján. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Megkeresi a szerzőt a gyűjteményben név és kezdőbetűk alapján. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a szerzőt a gyűjtemény megadott indexén. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Eltávolítja a megadott szerző első előfordulását a gyűjteményben. |
| [clear()](#clear--) | Eltávolítja az összes szerzőt a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Lekéri az elemet a megadott indexnél. Csak olvasható [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Új szerzőt ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Az új szerző neve. |
| initials | java.lang.String | Az új szerző kezdőbetűi. |

**Visszatérési érték:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Új [ICommentAuthor](../../com.aspose.slides/icommentauthor) objektum.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Létrehozza és visszaad egy tömböt az összes szerzővel.

**Visszatérési érték:**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) tömbje
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Megkeresi a szerzőt a gyűjteményben név alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresendő szerző neve. |

**Visszatérési érték:**
com.aspose.slides.ICommentAuthor[] - Szerző vagy null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Megkeresi a szerzőt a gyűjteményben név és kezdőbetűk alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresendő szerző neve. |
| initials | java.lang.String | A keresendő szerző kezdőbetűi. |

**Visszatérési érték:**
com.aspose.slides.ICommentAuthor[] - Szerző vagy null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a szerzőt a gyűjtemény megadott indexén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nulláktól induló indexe. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Eltávolítja a megadott szerző első előfordulását a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | A gyűjteményből eltávolítandó szerző. |

### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja az összes szerzőt a gyűjteményből.