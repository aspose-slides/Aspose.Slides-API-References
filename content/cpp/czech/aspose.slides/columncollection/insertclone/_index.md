---
title: InsertClone()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří kopii zadaného šablonového sloupce a vloží ji na zadanou pozici v tabulce.
type: docs
weight: 66
url: /cs/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metoda


Vytvoří kopii zadaného šablonového sloupce a vloží ji na zadanou pozici v tabulce.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového sloupce. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) který je používán jako šablona. |
| withAttachedColumns | **bool** | True pro kopírování také všech sloupců připojených k šablonovému sloupci. |

### Návratová hodnota

Vložené sloupce.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IColumn](../../icolumn/)
* Třída [ColumnCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)