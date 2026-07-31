---
title: SelectChildren()
second_title: Aspose.Slides untuk Referensi API C++
description: Memilih semua node anak dari node saat ini yang memiliki XPathNodeType yang cocok.
type: docs
weight: 833
url: /id/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) metode

Memilih semua node anak dari node saat ini yang memiliki XPathNodeType yang cocok.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType dari node anak. |

### Nilai Kembalian

Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang berisi node yang dipilih.

## XPathNavigator::SelectChildren(String, String) metode

Memilih semua node anak dari node saat ini yang memiliki nama lokal dan namespace URI yang ditentukan.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lokal dari node anak. |
| namespaceURI | [String](../../../system/string/) | Namespace URI dari node anak. |

### Nilai Kembalian

Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang berisi node yang dipilih.

## Lihat Juga

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)