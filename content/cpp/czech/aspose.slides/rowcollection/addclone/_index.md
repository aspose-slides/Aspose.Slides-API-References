---
title: AddClone()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří kopii zadaného šablonového řádku a vloží ji na konec tabulky.
type: docs
weight: 53
url: /cs/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metoda

Vytvoří kopii zadaného šablonového řádku a vloží ji na konec tabulky.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) která se používá jako šablona. |
| withAttachedRows | **bool** | True pokud chcete také zkopírovat všechny řádky připojené k šablonovému řádku. |

### Návratová hodnota

Přidané řádky.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IRow](../../irow/)
* Třída [RowCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)