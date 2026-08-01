---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in.
type: docs
weight: 14
url: /nl/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) methode

Maakt een kopie van de opgegeven sjabloonrij en voegt deze toe aan de onderkant van een tabel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
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
* Class [IColumn](../../icolumn/)
* Class [IColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)