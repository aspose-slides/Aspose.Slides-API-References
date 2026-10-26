---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven sjabloonrij en voegt deze toe aan de onderkant van een tabel.
type: docs
weight: 53
url: /nl/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) methode


Maakt een kopie van de opgegeven sjabloonrij en voegt deze toe aan de onderkant van een tabel.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) die als sjabloon wordt gebruikt. |
| withAttachedColumns | **bool** | True om ook alle kolommen die aan de sjabloonrij zijn gekoppeld te kopiëren. |

### Retourwaarde

Toegevoegde kolommen.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColumn](../../icolumn/)
* Klasse [ColumnCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)