---
title: InsertClone()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří kopii zadaného šablonového sloupce a vloží ji na určenou pozici v tabulce.
type: docs
weight: 27
url: /cs/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metoda

Vytvoří kopii zadaného šablonového sloupce a vloží ji na určenou pozici v tabulce.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového sloupce. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) který se používá jako šablona. |
| withAttachedColumns | **bool** | True pro zkopírování také všech sloupců připojených k šablonovému sloupci. |

### Návratová hodnota

Vložené sloupce.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IColumn](../../icolumn/)
* třída [IColumnCollection](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)