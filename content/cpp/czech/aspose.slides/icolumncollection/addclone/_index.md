---
title: AddClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří kopii zadaného šablonového řádku a vloží ji na konec tabulky.
type: docs
weight: 14
url: /cs/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) metoda


Vytvoří kopii zadaného šablonového řádku a vloží ji na konec tabulky.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) který se používá jako šablona. |
| withAttachedColumns | **bool** | True pro zkopírování také všech sloupců připojených k šablonovému řádku. |

### Návratová hodnota

Přidané sloupce.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IColumn](../../icolumn/)
* Třída [IColumnCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)