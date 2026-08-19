---
title: ColumnCollection
second_title: Aspose.Slides pro Java – reference API
description: Representuje kolekci sloupců v tabulce.
type: docs
url: /cs/com.aspose.slides/columncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Represents collection of columns in a table.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet sloupců ve sbírce. |
| [get_Item(int index)](#get-Item-int-) | Vrací sloupec na zadaném indexu. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Vytvoří kopii zadaného řádku šablony a vloží ji na konec tabulky. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Vytvoří kopii zadaného sloupce šablony a vloží jej na zadanou pozici v tabulce. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Odstraní sloupec na zadané pozici z tabulky. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází sbírkou. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou sbírku. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky ze sbírky do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### size() {#size--}
```
public final int size()
```

Vrací počet sloupců ve sbírce. Pouze ke čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Vrací sloupec na zadaném indexu. Pouze ke čtení [Column](../../com.aspose.slides/column).

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

Vytvoří kopii zadaného řádku šablony a vloží ji na konec tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Sloupec, který je použit jako šablona. |
| withAttachedColumns | boolean | True to copy also all columns attached to the template row. |

**Vrací:**
com.aspose.slides.IColumn[] - Přidané sloupce.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Vytvoří kopii zadaného sloupce šablony a vloží jej na zadanou pozici v tabulce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového sloupce. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Sloupec, který je použit jako šablona. |
| withAttachedColumns | boolean | True to copy also all columns attached to the template column. |

**Vrací:**
com.aspose.slides.IColumn[] - Vložené sloupce.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Odstraní sloupec na zadané pozici z tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| firstColumnIndex | int | Index sloupce k odstranění. |
| withAttachedRows | boolean | True to delete also all attached columns. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Vrací enumerátor, který prochází sbírkou.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - IGenericEnumerator, který lze použít k iteraci přes sbírku.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Vrací java iterátor pro celou sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator pro celou sbírku.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky ze sbírky do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object