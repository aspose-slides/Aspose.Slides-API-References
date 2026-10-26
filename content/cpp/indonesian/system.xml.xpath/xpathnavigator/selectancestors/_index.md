---
title: SelectAncestors()
second_title: Aspose.Slides untuk Referensi API C++
description: Memilih semua node leluhur dari node saat ini yang memiliki XPathNodeType yang cocok.
type: docs
weight: 846
url: /id/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) metode

Memilih semua node leluhur dari node saat ini yang memiliki XPathNodeType yang cocok.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType dari node leluhur. |
| matchSelf | **bool** | Untuk menyertakan node konteks dalam pemilihan, **true**; jika tidak, **false**. |

### Nilai Kembalian

Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang berisi node yang dipilih. Node yang dikembalikan berada dalam urutan dokumen terbalik.

## XPathNavigator::SelectAncestors(String, String, bool) metode

Memilih semua node leluhur dari node saat ini yang memiliki nama lokal dan URI ruang nama yang ditentukan.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lokal dari node leluhur. |
| namespaceURI | [String](../../../system/string/) | URI ruang nama dari node leluhur. |
| matchSelf | **bool** | Untuk menyertakan node konteks dalam pemilihan, **true**; jika tidak, **false**. |

### Nilai Kembalian

Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang berisi node yang dipilih. Node yang dikembalikan berada dalam urutan dokumen terbalik.

## Lihat Juga

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XPathNodeIterator](../../xpathnodeiterator/)
* Kelas [XPathNavigator](../)
* Kelas [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)