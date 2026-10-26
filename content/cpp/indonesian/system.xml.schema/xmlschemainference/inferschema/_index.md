---
title: InferSchema()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyimpulkan skema XML Schema Definition Language (XSD) dari dokumen XML yang terdapat dalam objek XmlReader yang ditentukan.
type: docs
weight: 66
url: /id/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) metode

Menyimpulkan skema XML [Schema](../../) Definition Language (XSD) dari dokumen XML yang terdapat dalam objek [XmlReader](../../../system.xml/xmlreader/) yang ditentukan.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objek [XmlReader](../../../system.xml/xmlreader/) yang berisi dokumen XML untuk disimpulkan skemanya. |

### Nilai Kembalian

Objek [XmlSchemaSet](../../xmlschemaset/) yang berisi skema yang disimpulkan.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) metode

Menyimpulkan skema XML [Schema](../../) Definition Language (XSD) dari dokumen XML yang terdapat dalam objek [XmlReader](../../../system.xml/xmlreader/) yang ditentukan, dan memperbaiki skema yang disimpulkan menggunakan skema yang ada dalam objek [XmlSchemaSet](../../xmlschemaset/) yang ditentukan dengan namespace target yang sama.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objek [XmlReader](../../../system.xml/xmlreader/) yang berisi dokumen XML untuk disimpulkan skemanya. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Objek [XmlSchemaSet](../../xmlschemaset/) yang berisi skema yang ada yang digunakan untuk memperbaiki skema yang disimpulkan. |

### Nilai Kembalian

Objek [XmlSchemaSet](../../xmlschemaset/) yang berisi skema yang disimpulkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlSchemaSet](../../xmlschemaset/)
* Kelas [XmlReader](../../../system.xml/xmlreader/)
* Kelas [XmlSchemaInference](../)
* Ruang nama [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)