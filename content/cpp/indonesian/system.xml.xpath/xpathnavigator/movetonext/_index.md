---
title: MoveToNext()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride di kelas turunan, memindahkan XPathNavigator ke node saudara berikutnya dari node saat ini.
type: docs
weight: 586
url: /id/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() metode

Saat dioverride di kelas turunan, memindahkan [XPathNavigator](../) ke node saudara berikutnya dari node saat ini.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil dipindahkan ke node saudara berikutnya; **false** jika tidak ada saudara lagi atau jika [XPathNavigator](../) sedang berada pada node atribut. Jika **false**, posisi [XPathNavigator](../) tidak berubah.

## XPathNavigator::MoveToNext(String, String) metode

Memindahkan [XPathNavigator](../) ke node saudara berikutnya dengan nama lokal dan namespace URI yang ditentukan.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal node saudara berikutnya yang akan dipindahkan ke. |
| namespaceURI | [String](../../../system/string/) | Namespace URI node saudara berikutnya yang akan dipindahkan ke. |

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil dipindahkan ke node saudara berikutnya; **false** jika tidak ada saudara lagi, atau jika [XPathNavigator](../) sedang berada pada node atribut. Jika **false**, posisi [XPathNavigator](../) tidak berubah.

## XPathNavigator::MoveToNext(XPathNodeType) metode

Memindahkan [XPathNavigator](../) ke node saudara berikutnya dari node saat ini yang sesuai dengan XPathNodeType yang ditentukan.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType dari node saudara yang akan dipindahkan ke. |

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil dipindahkan ke node saudara berikutnya; **false** jika tidak ada saudara lagi atau jika [XPathNavigator](../) sedang berada pada node atribut. Jika **false**, posisi [XPathNavigator](../) tidak berubah.

## Lihat Juga

* Enum [XPathNodeType](../../xpathnodetype/)
* Kelas [XPathNavigator](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Xml::XPath](../../)
* Perpustakaan [Aspose.Slides](../../../)