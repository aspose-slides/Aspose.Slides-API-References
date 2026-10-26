---
title: ChangeType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai yang ditentukan, yang tipenya merupakan salah satu representasi valid dari tipe skema XML yang direpresentasikan oleh XmlSchemaDatatype, ke tipe waktu jalan yang ditentukan.
type: docs
weight: 66
url: /id/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method

Mengonversi nilai yang ditentukan, yang tipenya merupakan salah satu representasi valid dari tipe skema XML yang direpresentasikan oleh [XmlSchemaDatatype](../), ke tipe waktu jalan yang ditentukan.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Nilai masukan yang akan dikonversi ke tipe yang ditentukan. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Tipe target untuk mengonversi nilai masukan. |

### Nilai Kembalian

Nilai masukan yang telah dikonversi.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

Mengonversi nilai yang ditentukan, yang tipenya merupakan salah satu representasi valid dari tipe skema XML yang direpresentasikan oleh [XmlSchemaDatatype](../), ke tipe waktu jalan yang ditentukan menggunakan [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) jika [XmlSchemaDatatype](../) merepresentasikan tipe **xs:QName** atau tipe yang diturunkan darinya.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Nilai masukan yang akan dikonversi ke tipe yang ditentukan. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Tipe target untuk mengonversi nilai masukan. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Sebuah [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan prefiks namespace. Ini hanya berguna jika [XmlSchemaDatatype](../) merepresentasikan tipe **xs:QName** atau tipe yang diturunkan darinya. |

### Nilai Kembalian

Nilai masukan yang telah dikonversi.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [XmlSchemaDatatype](../)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::Schema](../../)
* Pustaka [Aspose.Slides](../../../)