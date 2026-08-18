---
title: ICommentAuthorCollection
second_title: Aspose.Slides Java API referencia
description: Megjegyzés-szerzők gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/icommentauthorcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Egy megjegyzés-szerzők gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Új szerzőt ad a gyűjtemény végéhez. |
| [toArray()](#toArray--) | Létrehozza és visszaadja a tömböt az összes szerzővel. |
| [findByName(String name)](#findByName-java.lang.String-) | Szerzőt keres a gyűjteményben név alapján. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Szerzőt keres a gyűjteményben név és kezdőbetűk alapján. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a szerzőt a megadott indexnél a gyűjteményből. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Eltávolítja a megadott szerző első előfordulását a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes szerzőt a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak olvasható [ICommentAuthor](../../com.aspose.slides/icommentauthor).

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
[ICommentAuthor](../../com.aspose.slides/icommentauthor) – Új [ICommentAuthor](../../com.aspose.slides/icommentauthor) objektum.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

Létrehozza és visszaadja a tömböt az összes szerzővel.

**Visszatérési érték:**
com.aspose.slides.ICommentAuthor[] – Tömb a(z) [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

Szerzőt keres a gyűjteményben név alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresett szerző neve. |

**Visszatérési érték:**
com.aspose.slides.ICommentAuthor[] – Szerző vagy null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Szerzőt keres a gyűjteményben név és kezdőbetűk alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresett szerző neve. |
| initials | java.lang.String | A keresett szerző kezdőbetűi. |

**Visszatérési érték:**
com.aspose.slides.ICommentAuthor[] – Szerző vagy null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a szerzőt a megadott indexnél a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nulla-alapú indexe. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

Eltávolítja a megadott szerző első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | A gyűjteményből eltávolítandó szerző. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes szerzőt a gyűjteményből.