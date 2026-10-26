---
title: AddClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří kopii zadaného řádku šablony a vloží ji na konec tabulky.
type: docs
weight: 14
url: /cs/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metoda


Vytvoří kopii zadaného řádku šablony a vloží ji na konec tabulky.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) který je použit jako šablona. |
| withAttachedRows | **bool** | True to copy also all rows attached to the template row. |

### Návratová hodnota

Přidané řádky.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IRow](../../irow/)
* Třída [IRowCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)