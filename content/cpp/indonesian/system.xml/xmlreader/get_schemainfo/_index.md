---
title: get_SchemaInfo()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan informasi skema yang telah ditetapkan pada node saat ini sebagai hasil validasi skema.
type: docs
weight: 196
url: /id/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() metode


Mengembalikan informasi skema yang telah ditetapkan pada node saat ini sebagai hasil validasi skema.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### Nilai Kembalian

Sebuah objek IXmlSchemaInfo yang berisi informasi skema untuk node saat ini. [Schema](../../../system.xml.schema/) informasi dapat diatur pada elemen, atribut, atau pada node teks dengan nilai [XmlReader::get_ValueType](../get_valuetype/) yang tidak null. Jika node saat ini bukan salah satu tipe node di atas, atau jika instance [XmlReader](../) tidak melaporkan informasi skema, metode ini mengembalikan **nullptr**. Jika metode ini dipanggil dari objek [XmlTextReader](../../xmltextreader/) atau objek [XmlValidatingReader](../../xmlvalidatingreader/), metode ini selalu mengembalikan **nullptr**. Implementasi [XmlReader](../) ini tidak mengekspos informasi skema melalui metode get_SchemaInfo.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)