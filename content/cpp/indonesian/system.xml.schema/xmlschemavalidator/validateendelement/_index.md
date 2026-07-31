---
title: ValidateEndElement()
second_title: Referensi API Aspose.Slides untuk C++
description: Memverifikasi apakah konten teks elemen valid menurut tipe datanya untuk elemen dengan konten sederhana, dan memverifikasi apakah konten elemen saat ini lengkap untuk elemen dengan konten kompleks.
type: docs
weight: 209
url: /id/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) metode


Memverifikasi apakah konten teks elemen valid menurut tipe datanya untuk elemen dengan konten sederhana, dan memverifikasi apakah konten elemen saat ini lengkap untuk elemen dengan konten kompleks.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Sebuah objek [XmlSchemaInfo](../../xmlschemainfo/) yang propertinya diatur pada validasi elemen yang berhasil. Parameter ini dapat berupa **nullptr**. |

### Nilai Kembalian

Nilai teks yang diparsing dan bertipe dari elemen bila elemen memiliki konten sederhana.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) metode


Memverifikasi apakah konten teks elemen yang ditentukan valid menurut tipe datanya.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Sebuah objek [XmlSchemaInfo](../../xmlschemainfo/) yang propertinya diatur pada validasi konten teks elemen yang berhasil. Parameter ini dapat berupa **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Konten teks yang bertipe dari elemen. |

### Nilai Kembalian

Konten sederhana yang diparsing dan bertipe dari elemen.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)