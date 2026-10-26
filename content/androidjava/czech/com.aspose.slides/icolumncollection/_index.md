---
title: IColumnCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Představuje kolekci sloupců v tabulce.
type: docs
url: /cs/com.aspose.slides/icolumncollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Představuje kolekci sloupců v tabulce.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací sloupec na zadaném indexu. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Vytvoří kopii zadaného šablonového řádku a vloží ji na konec tabulky. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Vytvoří kopii zadaného šablonového sloupce a vloží ji na zadanou pozici v tabulce. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Odstraní sloupec na zadané pozici z tabulky. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


Vrací sloupec na zadaném indexu. Pouze pro čtení [IColumn](../../com.aspose.slides/icolumn).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Vytvoří kopii zadaného šablonového řádku a vloží ji na konec tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Sloupec, který se používá jako šablona. |
| withAttachedColumns | boolean | True, pokud chcete zkopírovat také všechny sloupce připojené k šablonovému řádku. |

**Návratová hodnota:**
com.aspose.slides.IColumn[] - Přidané sloupce.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Vytvoří kopii zadaného šablonového sloupce a vloží ji na zadanou pozici v tabulce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového sloupce. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Sloupec, který se používá jako šablona. |
| withAttachedColumns | boolean | True, pokud chcete zkopírovat také všechny sloupce připojené k šablonovému sloupci. |

**Návratová hodnota:**
com.aspose.slides.IColumn[] - Vložené sloupce.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Odstraní sloupec na zadané pozici z tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| firstColumnIndex | int | Index sloupce, který se má smazat. |
| withAttachedRows | boolean | True, pokud chcete smazat také všechny připojené sloupce. |