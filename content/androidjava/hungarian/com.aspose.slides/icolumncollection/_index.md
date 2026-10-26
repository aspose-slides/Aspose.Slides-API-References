---
title: IColumnCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: A táblázat oszlopainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/icolumncollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

A táblázat oszlopainak gyűjteményét képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az oszlopot a megadott indexnél. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára illeszti. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Létrehoz egy másolatot a megadott sablon oszlopból, és a táblázat meghatározott pozíciójába illeszti. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Eltávolít egy oszlopot a táblázat meghatározott pozíciójából. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Visszaadja az oszlopot a megadott indexnél. Csak olvasható [IColumn](../../com.aspose.slides/icolumn).

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

Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | A sablonként használt oszlop. |
| withAttachedColumns | boolean | True, ha másolja az összes a sablon sorhoz csatolt oszlopot. |

**Visszatérési érték:**
com.aspose.slides.IColumn[] - Hozzáadott oszlopok.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Létrehoz egy másolatot a megadott sablon oszlopból, és a táblázat meghatározott pozíciójába illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új oszlop indexe. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | A sablonként használt oszlop. |
| withAttachedColumns | boolean | True, ha másolja az összes a sablon oszlophoz csatolt oszlopot. |

**Visszatérési érték:**
com.aspose.slides.IColumn[] - Beszúrt oszlopok.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Eltávolít egy oszlopot a táblázat meghatározott pozíciójából.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstColumnIndex | int | A törlendő oszlop indexe. |
| withAttachedRows | boolean | True, ha törli az összes csatolt oszlopot. |