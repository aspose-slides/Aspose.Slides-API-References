---
title: IRowCollection
second_title: Aspose.Slides Androidra Java API hivatkozás
description: A táblázat sorok gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/irowcollection/
---
**Az összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

A táblázat sorok gyűjteményét reprezentálja.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az elemet a megadott indexen. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára helyezi be. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Létrehoz egy másolatot a megadott sablon sorból, és a táblázat megadott pozíciójába illeszti be. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Eltávolít egy sor a táblázat megadott pozíciójából. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Visszaadja az elemet a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára helyezi be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | A sablonként használt sor. |
| withAttachedRows | boolean | Igaz, ha a sablon sorhoz csatolt összes sort is másolni kell. |

**Visszatérési érték:**
com.aspose.slides.IRow[] - Hozzáadott sorok.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Létrehoz egy másolatot a megadott sablon sorból, és a táblázat megadott pozíciójába illeszti be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Új sor indexe. |
| templ | [IRow](../../com.aspose.slides/irow) | A sablonként használt sor. |
| withAttachedRows | boolean | Igaz, ha a sablon sorhoz csatolt összes sort is másolni kell. |

**Visszatérési érték:**
com.aspose.slides.IRow[] - Beszúrt sorok.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Eltávolít egy sor a táblázat megadott pozíciójából.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstRowIndex | int | A törlendő sor indexe. |
| withAttachedRows | boolean | Igaz, ha az összes csatolt sort is törölni kell. |
