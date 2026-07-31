---
title: Validate()
second_title: Referensi API Aspose.Slides untuk C++
description: "Memvalidasi XmlDocument terhadap skema XML Schema Definition Language (XSD) yang terdapat dalam daftar XmlDocument::get_Schemas."
type: docs
weight: 573
url: /id/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) metode

Memvalidasi [XmlDocument](../) terhadap skema XML [Schema](../../../system.xml.schema/) Definition Language (XSD) yang terdapat dalam daftar [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Objek [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) yang menerima informasi tentang peringatan dan kesalahan validasi skema. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) metode

Memvalidasi objek [XmlNode](../../xmlnode/) yang ditentukan terhadap skema XML [Schema](../../../system.xml.schema/) Definition Language (XSD) dalam daftar [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Objek [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) yang menerima informasi tentang peringatan dan kesalahan validasi skema. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Objek [XmlNode](../../xmlnode/) yang dibuat dari sebuah [XmlDocument](../) untuk divalidasi. |

## Lihat Juga

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlDocument](../)
* Kelas [XmlNode](../../xmlnode/)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)