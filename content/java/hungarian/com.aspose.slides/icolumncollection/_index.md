---
title: IColumnCollection
second_title: Aspose.Slides Java API referenciája
description: A táblázat oszlopainak gyűjteménye.
type: docs
url: /hu/com.aspose.slides/icolumncollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

A táblázat oszlopainak gyűjteménye.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű oszlopot. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Létrehozza a megadott sablon sor másolatát, és a táblázat aljára helyezi. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Létrehozza a megadott sablon oszlop másolatát, és a táblázat megadott pozíciójába szúrja be. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Eltávolít egy oszlopot a táblázat megadott pozíciójából. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


Visszaadja a megadott indexű oszlopot. Csak olvasható [IColumn](../../com.aspose.slides/icolumn).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Létrehozza a megadott sablon sor másolatát, és a táblázat aljára helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | A sablonként használt oszlop. |
| withAttachedColumns | boolean | True, ha a sablon sorhoz csatolt összes oszlopot is másolni szeretné. |

**Visszatérési érték:**
com.aspose.slides.IColumn[] - Hozzáadott oszlopok.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Létrehozza a megadott sablon oszlop másolatát, és a táblázat megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új oszlop indexe. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | A sablonként használt oszlop. |
| withAttachedColumns | boolean | True, ha a sablon oszlophoz csatolt összes oszlopot is másolni szeretné. |

**Visszatérési érték:**
com.aspose.slides.IColumn[] - Beszúrt oszlopok.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Eltávolít egy oszlopot a táblázat megadott pozíciójából.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstColumnIndex | int | Az eltávolítandó oszlop indexe. |
| withAttachedRows | boolean | True, ha a csatolt oszlopokat is törölni szeretné. |