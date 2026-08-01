---
title: InsertClone()
second_title: Aspose.Slides for C++ API Referentie
description: Maakt een kopie van de opgegeven sjabloonkolom en voegt deze in op de opgegeven positie in een tabel.
type: docs
weight: 66
url: /nl/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method

Maakt een kopie van de opgegeven sjabloonkolom en voegt deze in op de opgegeven positie in een tabel.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index van een nieuwe kolom. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) die wordt gebruikt als sjabloon. |
| withAttachedColumns | **bool** | True om ook alle kolommen die aan de sjabloonkolom zijn gekoppeld te kopiëren. |

### Retourwaarde

Ingevoegde kolommen.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColumn](../../icolumn/)
* Klasse [ColumnCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)