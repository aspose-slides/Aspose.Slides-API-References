---
title: IColumnCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci sloupců v tabulce.
type: docs
url: /cs/com.aspose.slides/icolumncollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Reprezentuje kolekci sloupců v tabulce.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací sloupec na určeném indexu. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Vytvoří kopii zadaného šablonového řádku a vloží ji na konec tabulky. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Vytvoří kopii zadaného šablonového sloupce a vloží ji na určenou pozici v tabulce. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Odstraní sloupec na určené pozici z tabulky. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Vrací sloupec na určeném indexu. Pouze pro čtení [IColumn](../../com.aspose.slides/icolumn).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
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
| withAttachedColumns | boolean | True, pokud se mají také zkopírovat všechny sloupce připojené k šablonovému řádku. |

**Vrací:**
com.aspose.slides.IColumn[] - Přidané sloupce.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Vytvoří kopii zadaného šablonového sloupce a vloží ji na určenou pozici v tabulce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového sloupce. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Sloupec, který se používá jako šablona. |
| withAttachedColumns | boolean | True, pokud se mají také zkopírovat všechny sloupce připojené k šablonovému sloupci. |

**Vrací:**
com.aspose.slides.IColumn[] - Vložené sloupce.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Odstraní sloupec na určené pozici z tabulky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| firstColumnIndex | int | Index sloupce k odstranění. |
| withAttachedRows | boolean | True, pokud se mají také odstranit všechny připojené sloupce. |