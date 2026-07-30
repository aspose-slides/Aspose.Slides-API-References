---
title: InsertClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří kopii zadaného řádku šablony a vloží ji na určenou pozici v tabulce.
type: docs
weight: 27
url: /cs/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metoda

Vytvoří kopii zadaného řádku šablony a vloží ji na určenou pozici v tabulce.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového řádku. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) který se používá jako šablona. |
| withAttachedRows | **bool** | True pro kopírování také všech řádků připojených k řádku šablony. |

### Návratová hodnota

Vložené řádky.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IRow](../../irow/)
* Třída [IRowCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)