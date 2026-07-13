---
title: ColumnCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje kolekci sloupců v tabulce.
type: docs
url: /cs/com.aspose.slides/columncollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Reprezentuje kolekci sloupců v tabulce.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet sloupců v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací sloupec na zadaném indexu. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Vytvoří kopii zadaného šablonového řádku a vloží ji na konec tabulky. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Vytvoří kopii zadaného šablonového sloupce a vloží ji na zadanou pozici v tabulce. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Odstraňuje sloupec na zadané pozici z tabulky. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací synchronizační kořen. |
### size() {#size--}
```
public final int size()
```


Vrací počet sloupců v kolekci. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


Vrací sloupec na zadaném indexu. Pouze pro čtení [Column](../../com.aspose.slides/column).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Vytvoří kopii zadaného šablonového řádku a vloží ji na konec tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Sloupec, který se používá jako šablona. |
| withAttachedColumns | boolean | True, pokud chcete také zkopírovat všechny sloupce připojené k šablonovému řádku. |

**Vrací:**
com.aspose.slides.IColumn[] - Přidané sloupce.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Vytvoří kopii zadaného šablonového sloupce a vloží ji na zadanou pozici v tabulce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového sloupce. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Sloupec, který se používá jako šablona. |
| withAttachedColumns | boolean | True, pokud chcete také zkopírovat všechny sloupce připojené k šablonovému sloupci. |

**Vrací:**
com.aspose.slides.IColumn[] - Vložené sloupce.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Odstraňuje sloupec na zadané pozici z tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| firstColumnIndex | int | Index sloupce k smazání. |
| withAttachedRows | boolean | True, pokud chcete také smazat všechny připojené sloupce. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator pro celou kolekci.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací synchronizační kořen. Pouze pro čtení Object.

**Vrací:**
java.lang.Object