---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in.
type: docs
weight: 53
url: /nl/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) methode

Maakt een kopie van de gespecificeerde sjabloonrij en voegt deze onderaan een tabel in.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
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
* Klasse [IRow](../../irow/)
* Klasse [RowCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)