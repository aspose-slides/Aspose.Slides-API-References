---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan skema bahasa definisi XML Schema (XSD) pada URL yang ditentukan ke XmlSchemaSet.
type: docs
weight: 157
url: /id/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) metode

Menambahkan skema XML [Schema](../../) definition language (XSD) pada URL yang ditentukan ke [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Nilai **targetNamespace** skema, atau **nullptr** untuk menggunakan **targetNamespace** yang ditentukan dalam skema. |
| schemaUri | const [String](../../../system/string/)\& | URL yang menentukan skema yang akan dimuat. |

### Nilai Kembalian

Objek [XmlSchema](../../xmlschema/) jika skema valid. Jika skema tidak valid dan ValidationEventHandler ditentukan, maka **nullptr** dikembalikan dan peristiwa validasi yang sesuai akan dipicu. Jika tidak, XmlSchemaException dilempar.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) metode

Menambahkan skema XML [Schema](../../) definition language (XSD) yang terdapat dalam [XmlReader](../../../system.xml/xmlreader/) ke [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Nilai **targetNamespace** skema, atau **nullptr** untuk menggunakan **targetNamespace** yang ditentukan dalam skema. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objek [XmlReader](../../../system.xml/xmlreader/). |

### Nilai Kembalian

Objek [XmlSchema](../../xmlschema/) jika skema valid. Jika skema tidak valid dan ValidationEventHandler ditentukan, maka **nullptr** dikembalikan dan peristiwa validasi yang sesuai akan dipicu. Jika tidak, XmlSchemaException dilempar.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) metode

Menambahkan semua skema XML [Schema](../../) definition language (XSD) dalam [XmlSchemaSet](../) yang diberikan ke [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | Objek [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) metode

Menambahkan [XmlSchema](../../xmlschema/) yang diberikan ke [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Objek [XmlSchema](../../xmlschema/) untuk ditambahkan ke [XmlSchemaSet](../). |

### Nilai Kembalian

Objek [XmlSchema](../../xmlschema/) jika skema valid. Jika skema tidak valid dan ValidationEventHandler ditentukan, maka **nullptr** dikembalikan dan peristiwa validasi yang sesuai akan dipicu. Jika tidak, XmlSchemaException dilempar.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)