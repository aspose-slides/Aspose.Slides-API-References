---
title: IRowCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje kolekci řádků tabulky.
type: docs
url: /cs/com.aspose.slides/irowcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Reprezentuje kolekci řádků tabulky.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Creates a copy of the specified template row and insert it at the specified position in a table. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Removes a row at the specified position from a table. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Získá prvek na určeném indexu.

**Parametry:**
| Parameter | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Vytvoří kopii určeného šablonového řádku a vloží ji na konec tabulky.

**Parametry:**
| Parameter | Typ | Popis |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Řádek používaný jako šablona. |
| withAttachedRows | boolean | True pro zkopírování také všech řádků připojených k šablonovému řádku. |

**Vrací:**
IRow[] - Přidané řádky.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Vytvoří kopii určeného šablonového řádku a vloží ji na určenou pozici v tabulce.

**Parametry:**
| Parameter | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového řádku. |
| templ | [IRow](../../com.aspose.slides/irow) | Řádek používaný jako šablona. |
| withAttachedRows | boolean | True pro zkopírování také všech řádků připojených k šablonovému řádku. |

**Vrací:**
IRow[] - Vložené řádky.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Odstraní řádek na určené pozici z tabulky.

**Parametry:**
| Parameter | Typ | Popis |
| --- | --- | --- |
| firstRowIndex | int | Index řádku, který má být smazán. |
| withAttachedRows | boolean | True pro smazání také všech připojených řádků. |