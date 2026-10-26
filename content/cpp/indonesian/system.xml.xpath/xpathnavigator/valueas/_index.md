---
title: ValueAs()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai node saat ini sebagai Type yang ditentukan, menggunakan objek IXmlNamespaceResolver yang ditentukan untuk menyelesaikan prefix namespace.
type: docs
weight: 378
url: /id/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metode

Mengembalikan nilai node saat ini sebagai Type yang ditentukan, menggunakan objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk menyelesaikan prefix namespace.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Type untuk mengembalikan nilai node saat ini sebagai. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan prefix namespace. |

### Nilai Kembali

Nilai node saat ini sebagai Type yang diminta.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Kelas [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Perpustakaan [Aspose.Slides](../../../)