---
title: MoveToChild()
second_title: Referensi API Aspose.Slides untuk C++
description: Memindahkan XPathNavigator ke node anak dengan nama lokal dan namespace URI yang ditentukan.
type: docs
weight: 690
url: /id/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) metode

Memindahkan [XPathNavigator](../) ke node anak dengan nama lokal dan namespace URI yang ditentukan.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal node anak yang akan dipindahkan ke. |
| namespaceURI | [String](../../../system/string/) | URI namespace node anak yang akan dipindahkan ke. |

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil berpindah ke node anak; selain itu, **false**. Jika **false**, posisi [XPathNavigator](../) tidak berubah.

## XPathNavigator::MoveToChild(XPathNodeType) metode

Memindahkan [XPathNavigator](../) ke node anak dari XPathNodeType yang ditentukan.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType node anak yang akan dipindahkan ke. |

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil berpindah ke node anak; selain itu, **false**. Jika **false**, posisi [XPathNavigator](../) tidak berubah.

## Lihat Juga

* Enum [XPathNodeType](../../xpathnodetype/)
* Kelas [String](../../../system/string/)
* Kelas [XPathNavigator](../)
* Ruang Nama [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)