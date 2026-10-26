---
title: Contains()
second_title: Aspose.Slides untuk Referensi API C++
description: Menunjukkan apakah sebuah skema bahasa definisi XML Schema (XSD) dengan URI namespace target yang ditentukan berada di dalam XmlSchemaSet.
type: docs
weight: 196
url: /id/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) metode


Menunjukkan apakah skema definisi bahasa XML [Schema](../../) (XSD) dengan URI namespace target yang ditentukan berada di dalam [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Properti **targetNamespace** skema. |

### Nilai Kembali

**true** jika sebuah skema dengan URI namespace target yang ditentukan berada di dalam [XmlSchemaSet](../); jika tidak, **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) metode


Menunjukkan apakah objek [XmlSchema](../../xmlschema/) definisi bahasa XML [Schema](../../) (XSD) yang ditentukan berada di dalam [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Objek [XmlSchema](../../xmlschema/). |

### Nilai Kembali

**true** jika objek [XmlSchema](../../xmlschema/) berada di dalam [XmlSchemaSet](../); jika tidak, **false**.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [XmlSchemaSet](../)
* Kelas [XmlSchema](../../xmlschema/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)