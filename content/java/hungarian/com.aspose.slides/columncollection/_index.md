---
title: ColumnCollection
second_title: Aspose.Slides Java API Referencia
description: Egy táblázat oszlopainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/columncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

A táblázat oszlopainak gyűjteményét képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő oszlopok számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű oszlopot. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára helyezi. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Létrehoz egy másolatot a megadott sablon oszlopból, és a táblázat megadott pozíciójába szúrja be. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Eltávolít egy oszlopot a táblázat megadott pozíciójából. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigjárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökér objektumot. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben lévő oszlopok számát. Csak olvasható int.

**Visszatérési érték:**
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

**Visszatérési érték:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | A sablonként használt oszlop. |
| withAttachedColumns | boolean | Igaz, ha a sablon sorhoz csatolt összes oszlopot is másolni kell. |

**Visszatérési érték:**
com.aspose.slides.IColumn[] - Hozzáadott oszlopok.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Létrehoz egy másolatot a megadott sablon oszlopból, és a táblázat megadott pozíciójába szúrja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új oszlop indexe. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | A sablonként használt oszlop. |
| withAttachedColumns | boolean | Igaz, ha a sablon oszlophoz csatolt összes oszlopot is másolni kell. |

**Visszatérési érték:**
com.aspose.slides.IColumn[] - Beszúrt oszlopok.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Eltávolít egy oszlopot a táblázat megadott pozíciójából.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstColumnIndex | int | A törlendő oszlop indexe. |
| withAttachedRows | boolean | Igaz, ha az összes csatolt oszlopot is törölni kell. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Visszaad egy enumerátort, amely végigjárja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Egy IGenericEnumerator, amely a gyűjtemény bejárására használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Egy java.util.Iterator a teljes gyűjteményhez.
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

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökér objektumot. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object