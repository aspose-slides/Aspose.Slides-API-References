---
title: RowCollection
second_title: Aspose.Slides pro Android – referenční příručka Java API
description: Reprezentuje kolekci řádků tabulky.
type: docs
url: /cs/com.aspose.slides/rowcollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Reprezentuje kolekci řádků tabulky.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Získá počet řádků skutečně obsažených v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací řádek na zadaném indexu. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Vytvoří kopii zadaného řádku šablony a vloží ji na konec tabulky. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Vytvoří kopii zadaného řádku šablony a vloží ji na zadanou pozici v tabulce. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Odstraní řádek na zadané pozici z tabulky. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen pro synchronizaci. |
### size() {#size--}
```
public final int size()
```

Získá počet řádků skutečně obsažených v kolekci. Jen pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

Vrací řádek na zadaném indexu. Jen pro čtení [Row](../../com.aspose.slides/row).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Vytvoří kopii zadaného řádku šablony a vloží ji na konec tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Řádek, který je použit jako šablona. |
| withAttachedRows | boolean | True, pokud chcete zkopírovat i všechny řádky připojené k řádku šablony. |

**Vrací:**
com.aspose.slides.IRow[] - Přidané řádky.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Vytvoří kopii zadaného řádku šablony a vloží ji na zadanou pozici v tabulce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového řádku. |
| templ | [IRow](../../com.aspose.slides/irow) | Řádek, který je použit jako šablona. |
| withAttachedRows | boolean | True, pokud chcete zkopírovat i všechny řádky připojené k řádku šablony. |

**Vrací:**
com.aspose.slides.IRow[] - Vložené řádky.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Odstraní řádek na zadané pozici z tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| firstRowIndex | int | Index řádku ke smazání. |
| withAttachedRows | boolean | True, pokud chcete smazat i všechny připojené řádky. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

Vrací java iterator pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - java.util.Iterator pro celou kolekci.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu označující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Jen pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen pro synchronizaci. Jen pro čtení Object.

**Vrací:**
java.lang.Object