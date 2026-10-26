---
title: ValueAs()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai elemen atau atribut XML yang telah divalidasi sebagai tipe yang ditentukan menggunakan objek IXmlNamespaceResolver yang ditentukan untuk menyelesaikan prefiks namespace.
type: docs
weight: 144
url: /id/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metode

Mengembalikan nilai elemen atau atribut XML yang telah divalidasi sebagai tipe yang ditentukan menggunakan objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk menyelesaikan prefiks namespace.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Tipe untuk mengembalikan nilai elemen atau atribut XML yang telah divalidasi. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan prefiks namespace. |

### Nilai Kembali

Nilai elemen atau atribut XML yang telah divalidasi sesuai dengan tipe yang diminta.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Kelas [XmlAtomicValue](../)
* Namespace [System::Xml::Schema](../../)
* Pustaka [Aspose.Slides](../../../)