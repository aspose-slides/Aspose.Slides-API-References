---
title: Schemas()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan kumpulan semua skema bahasa definisi XML Schema (XSD) dalam XmlSchemaSet.
type: docs
weight: 248
url: /id/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() metode

Mengembalikan koleksi semua skema bahasa definisi XML [Schema](../../) (XSD) di [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### Nilai Kembalian

Objek IList yang berisi semua skema yang telah ditambahkan ke [XmlSchemaSet](../). Jika tidak ada skema yang ditambahkan ke [XmlSchemaSet](../), koleksi kosong dikembalikan.

## XmlSchemaSet::Schemas(String) metode

Mengembalikan koleksi semua skema bahasa definisi XML [Schema](../../) (XSD) di [XmlSchemaSet](../) yang termasuk dalam namespace yang diberikan.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Properti **targetNamespace** skema. |

### Nilai Kembalian

Objek IList yang berisi semua skema yang telah ditambahkan ke [XmlSchemaSet](../) yang termasuk dalam namespace yang diberikan. Jika tidak ada skema yang ditambahkan ke [XmlSchemaSet](../), koleksi kosong dikembalikan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Class [List](../../../system.collections.generic/list/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)