---
title: ColumnCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Táblázatban lévő oszlopok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/columncollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Az asztalban lévő oszlopok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő oszlopok számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű oszlopot. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára illeszti. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Létrehoz egy másolatot a megadott sablon oszlopból, és a táblázatban a megadott pozícióba illeszti. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Eltávolít egy oszlopot a táblázatban a megadott pozícióból. |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort az egész gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérpontot. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben lévő oszlopok számát. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Visszaadja a megadott indexű oszlopot. Csak olvasható [Column](../../com.aspose.slides/column).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Oszlop, amely sablonként szolgál. |
| withAttachedColumns | boolean | True érték esetén másolja a sablon sorhoz csatolt összes oszlopot is. |

**Visszatér:**
com.aspose.slides.IColumn[] - Added columns.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Létrehoz egy másolatot a megadott sablon oszlopból, és a táblázatban a megadott pozícióba illeszti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Új oszlop indexe. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Oszlop, amely sablonként szolgál. |
| withAttachedColumns | boolean | True érték esetén másolja a sablon oszlophoz csatolt összes oszlopot is. |

**Visszatér:**
com.aspose.slides.IColumn[] - Inserted columns.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Eltávolít egy oszlopot a táblázatban a megadott pozícióból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstColumnIndex | int | A törlendő oszlop indexe. |
| withAttachedRows | boolean | True érték esetén törli a csatolt összes oszlopot is. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Visszaad egy felsorolót, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Visszaad egy java iterátort az egész gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - An java.util.Iterator for the entire collection.
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

Visszaad egy szinkronizációs gyökérpontot. Csak olvasható Object.

**Visszatér:**
java.lang.Object