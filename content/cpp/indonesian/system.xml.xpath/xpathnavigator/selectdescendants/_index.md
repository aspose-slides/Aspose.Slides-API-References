---
title: SelectDescendants()
second_title: Aspose.Slides untuk Referensi API C++
description: Memilih semua node turunan dari node saat ini yang memiliki XPathNodeType yang cocok.
type: docs
weight: 859
url: /id/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) metode

Memilih semua node turunan dari node saat ini yang memiliki XPathNodeType yang cocok.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType dari node turunan. |
| matchSelf | **bool** | **true** untuk menyertakan node konteks dalam pemilihan; jika tidak, **false**. |

### Nilai Kembalian

Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang berisi node yang dipilih.

## XPathNavigator::SelectDescendants(String, String, bool) metode

Memilih semua node turunan dari node saat ini dengan nama lokal dan namespace URI yang ditentukan.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lokal dari node turunan. |
| namespaceURI | [String](../../../system/string/) | Namespace URI dari node turunan. |
| matchSelf | **bool** | **true** untuk menyertakan node konteks dalam pemilihan; jika tidak, **false**. |

### Nilai Kembalian

Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang berisi node yang dipilih.

## Lihat Juga

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XPathNodeIterator](../../xpathnodeiterator/)
* Kelas [XPathNavigator](../)
* Kelas [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)