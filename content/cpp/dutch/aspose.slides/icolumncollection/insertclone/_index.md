---
title: InsertClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven sjabloonkollom en voegt deze in op de opgegeven positie in een tabel.
type: docs
weight: 27
url: /nl/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method


Maakt een kopie van de opgegeven sjabloonkollom en voegt deze in op de opgegeven positie in een tabel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van een nieuwe kolom. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) die wordt gebruikt als sjabloon. |
| withAttachedColumns | **bool** | True om ook alle kolommen die aan de sjabloonkollom zijn gekoppeld te kopiëren. |

### Retourwaarde

Ingevoegde kolommen.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColumn](../../icolumn/)
* Klasse [IColumnCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)