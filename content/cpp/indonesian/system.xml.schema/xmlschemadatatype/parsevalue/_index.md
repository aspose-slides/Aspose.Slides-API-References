---
title: ParseValue()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat ditimpa dalam kelas turunan, memvalidasi string yang ditentukan terhadap tipe sederhana bawaan atau yang didefinisikan pengguna.
type: docs
weight: 53
url: /id/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) metode


Saat ditimpa dalam kelas turunan, memvalidasi **string** yang ditentukan terhadap tipe sederhana bawaan atau yang didefinisikan pengguna.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | [String](../../../system/string/) | **string** untuk memvalidasi terhadap tipe sederhana. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | [XmlNameTable](../../../system.xml/xmlnametable/) yang digunakan untuk atomisasi saat menguraikan **string** jika objek [XmlSchemaDatatype](../) ini mewakili tipe **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objek yang digunakan saat menguraikan **string** jika objek [XmlSchemaDatatype](../) ini mewakili tipe **xs:QName**. |

### Nilai Kembalian

[Object](../../../system/object/) yang dapat dikast secara aman ke tipe yang dikembalikan oleh panggilan [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [String](../../../system/string/)
* Kelas [XmlNameTable](../../../system.xml/xmlnametable/)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Kelas [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Perpustakaan [Aspose.Slides](../../../)