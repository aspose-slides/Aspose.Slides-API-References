---
title: Reprocess()
second_title: Referensi API Aspose.Slides untuk C++
description: Mereproses skema bahasa definisi XML Schema (XSD) yang sudah ada di XmlSchemaSet.
type: docs
weight: 222
url: /id/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) metode


Mereproses skema bahasa definisi XML [Schema](../../) (XSD) yang sudah ada di [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Skema yang akan diproses ulang. |

### Nilai Kembali

Objek [XmlSchema](../../xmlschema/) jika skema tersebut valid. Jika skema tidak valid dan ValidationEventHandler ditentukan, **nullptr** dikembalikan dan peristiwa validasi yang sesuai dipicu. Jika tidak, XmlSchemaException dilempar.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlSchema](../../xmlschema/)
* Kelas [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Perpustakaan [Aspose.Slides](../../../)