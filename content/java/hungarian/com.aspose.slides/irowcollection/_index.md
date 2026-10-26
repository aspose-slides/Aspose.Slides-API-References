---
title: IRowCollection
second_title: Aspose.Slides Java API referenciája
description: A táblázat sorainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/irowcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

A tábla sorainak gyűjteményét képviseli.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az adott indexű elemet. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Létrehozza a megadott sablonsor másolatát, és a táblázat aljára helyezi be. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Létrehozza a megadott sablonsor másolatát, és a táblázat megadott pozíciójára helyezi be. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Eltávolít egy sort a megadott pozícióból a táblázatból. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Visszaadja az adott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IRow](../../com.aspose.slides/irow)

### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Létrehozza a megadott sablonsor másolatát, és a táblázat aljára helyezi be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | A sablonként használt sor. |
| withAttachedRows | boolean | Igaz, ha a sablonsorhoz csatolt összes sort is másolni kell. |

**Visszatér:**
com.aspose.slides.IRow[] - Added rows.

### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Létrehozza a megadott sablonsor másolatát, és a táblázat megadott pozíciójára helyezi be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új sor indexe. |
| templ | [IRow](../../com.aspose.slides/irow) | A sablonként használt sor. |
| withAttachedRows | boolean | Igaz, ha a sablonsorhoz csatolt összes sort is másolni kell. |

**Visszatér:**
com.aspose.slides.IRow[] - Inserted rows.

### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Eltávolít egy sort a megadott pozícióból a táblázatból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstRowIndex | int | A törlendő sor indexe. |
| withAttachedRows | boolean | Igaz, ha a csatolt összes sort is törölni kell. |