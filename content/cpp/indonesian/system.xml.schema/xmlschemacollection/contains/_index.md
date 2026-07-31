---
title: Contains()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai yang menunjukkan apakah targetNamespace dari XmlSchema yang ditentukan berada dalam koleksi.
type: docs
weight: 66
url: /id/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Mengembalikan nilai yang menunjukkan apakah **targetNamespace** dari [XmlSchema](../../xmlschema/) yang ditentukan berada dalam koleksi.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Objek [XmlSchema](../../xmlschema/). |

### Return Value

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## XmlSchemaCollection::Contains(const String\&) method


Mengembalikan nilai yang menunjukkan apakah skema dengan namespace yang ditentukan berada dalam koleksi.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI ruang nama yang terkait dengan skema. Untuk XML Schemas, biasanya akan menjadi target namespace. |

### Return Value

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlSchema](../../xmlschema/)
* Kelas [XmlSchemaCollection](../)
* Kelas [String](../../../system/string/)
* Namespace [System::Xml::Schema](../../)
* Perpustakaan [Aspose.Slides](../../../)