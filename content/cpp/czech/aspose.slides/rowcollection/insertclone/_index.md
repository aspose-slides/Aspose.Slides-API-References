---
title: InsertClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří kopii zadaného řádku šablony a vloží ji na určenou pozici v tabulce.
type: docs
weight: 66
url: /cs/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metoda

Vytvoří kopii zadaného řádku šablony a vloží ji na určenou pozici v tabulce.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového řádku. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) který je použit jako šablona. |
| withAttachedRows | **bool** | True, pokud chcete také zkopírovat všechny řádky připojené k řádku šablony. |

### Návratová hodnota

Vložené řádky.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IRow](../../irow/)
* Třída [RowCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)