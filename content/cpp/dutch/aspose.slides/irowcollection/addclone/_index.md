---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven sjabloonrij en voegt deze toe aan de onderkant van een tabel.
type: docs
weight: 14
url: /nl/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) methode

Maakt een kopie van de opgegeven sjabloonrij en voegt deze toe aan de onderkant van een tabel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) die wordt gebruikt als sjabloon. |
| withAttachedRows | **bool** | True om ook alle rijen die aan de sjabloonrij zijn gekoppeld te kopiëren. |

### Retourwaarde

Toegevoegde rijen.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)