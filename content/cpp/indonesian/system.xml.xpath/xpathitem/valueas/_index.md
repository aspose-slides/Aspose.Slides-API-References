---
title: ValueAs()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai item sebagai tipe yang ditentukan.
type: docs
weight: 131
url: /id/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) metode

Mengembalikan nilai item sebagai tipe yang ditentukan.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Tipe untuk mengembalikan nilai item. |

### Nilai Kembalian

Nilai item sebagai tipe yang diminta.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metode

Saat ditimpa dalam kelas turunan, mengembalikan nilai item sebagai tipe yang ditentukan menggunakan objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk menyelesaikan awalan ruang nama.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Tipe untuk mengembalikan nilai item. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan awalan ruang nama. |

### Nilai Kembalian

Nilai item sebagai tipe yang diminta.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)