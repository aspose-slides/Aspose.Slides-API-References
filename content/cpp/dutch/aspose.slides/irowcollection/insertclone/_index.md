---
title: InsertClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven sjabloonrij en voegt deze in op de opgegeven positie in een tabel.
type: docs
weight: 27
url: /nl/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) methode


Maakt een kopie van de opgegeven sjabloonrij en voegt deze in op de opgegeven positie in een tabel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van een nieuwe rij. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) die wordt gebruikt als een sjabloon. |
| withAttachedRows | **bool** | True om ook alle rijen die aan de sjabloonrij gekoppeld zijn te kopiëren. |

### Retourwaarde

Ingevoegde rijen.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IRow](../../irow/)
* Klasse [IRowCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)