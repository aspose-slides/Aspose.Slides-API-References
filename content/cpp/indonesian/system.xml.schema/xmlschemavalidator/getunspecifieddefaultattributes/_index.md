---
title: GetUnspecifiedDefaultAttributes()
second_title: Referensi API Aspose.Slides untuk C++
description: "Memvalidasi kendala identitas pada atribut default dan mengisi List yang ditentukan dengan objek XmlSchemaAttribute untuk setiap atribut dengan nilai default yang belum pernah divalidasi sebelumnya menggunakan metode XmlSchemaValidator::ValidateAttribute dalam konteks elemen."
type: docs
weight: 157
url: /id/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) metode

Memvalidasi kendala identitas pada atribut default dan mengisi List yang ditentukan dengan objek [XmlSchemaAttribute](../../xmlschemaattribute/) untuk atribut apa pun dengan nilai default yang belum pernah divalidasi sebelumnya menggunakan metode [XmlSchemaValidator::ValidateAttribute](../validateattribute/) dalam konteks elemen.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | Sebuah List untuk diisi dengan objek [XmlSchemaAttribute](../../xmlschemaattribute/) untuk setiap atribut yang belum ditemui selama validasi dalam konteks elemen. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [List](../../../system.collections.generic/list/)
* Kelas [Object](../../../system/object/)
* Kelas [XmlSchemaValidator](../)
* Ruang Nama [System::Xml::Schema](../../)
* Perpustakaan [Aspose.Slides](../../../)