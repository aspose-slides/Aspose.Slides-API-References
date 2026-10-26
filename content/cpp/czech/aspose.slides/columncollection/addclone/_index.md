---
title: AddClone()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří kopii určeného řádku šablony a vloží ji na konec tabulky.
type: docs
weight: 53
url: /cs/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method

Vytvoří kopii určeného řádku šablony a vloží ji na konec tabulky.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) který se používá jako šablona. |
| withAttachedColumns | **bool** | True k zkopírování také všech sloupců připojených k řádku šablony. |

### Návratová hodnota

Přidané sloupce.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IColumn](../../icolumn/)
* Třída [ColumnCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)