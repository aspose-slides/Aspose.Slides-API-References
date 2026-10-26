---
title: IRowCollection
second_title: Aspose.Slides pro Java API Reference
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
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Vytvoří kopii zadaného řádku šablony a vloží ji na konec tabulky. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Vytvoří kopii zadaného řádku šablony a vloží ji na zadanou pozici v tabulce. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Odstraní řádek na zadané pozici z tabulky. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Získá prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Vytvoří kopii zadaného řádku šablony a vloží ji na konec tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Řádek, který je použit jako šablona. |
| withAttachedRows | boolean | True pro kopírování také všech řádků připojených k řádku šablony. |

**Návratová hodnota:**
com.aspose.slides.IRow[] - Přidané řádky.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Vytvoří kopii zadaného řádku šablony a vloží ji na zadanou pozici v tabulce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového řádku. |
| templ | [IRow](../../com.aspose.slides/irow) | Řádek, který je použit jako šablona. |
| withAttachedRows | boolean | True pro kopírování také všech řádků připojených k řádku šablony. |

**Návratová hodnota:**
com.aspose.slides.IRow[] - Vložené řádky.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Odstraní řádek na zadané pozici z tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| firstRowIndex | int | Index řádku k odstranění. |
| withAttachedRows | boolean | True pro smazání také všech připojených řádků. |