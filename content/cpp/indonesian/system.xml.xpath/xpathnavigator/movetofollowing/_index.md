---
title: MoveToFollowing()
second_title: Referensi API Aspose.Slides untuk C++
description: Memindahkan XPathNavigator ke elemen dengan nama lokal dan URI namespace yang ditentukan dalam urutan dokumen.
type: docs
weight: 703
url: /id/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) metode

Memindahkan [XPathNavigator](../) ke elemen dengan nama lokal dan URI namespace yang ditentukan dalam urutan dokumen.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal elemen. |
| namespaceURI | [String](../../../system/string/) | URI namespace elemen. |

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil dipindahkan; selainnya, **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) metode

Memindahkan [XPathNavigator](../) ke elemen dengan nama lokal dan URI namespace yang ditentukan, ke batas yang ditentukan, dalam urutan dokumen.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal elemen. |
| namespaceURI | [String](../../../system/string/) | URI namespace elemen. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objek [XPathNavigator](../) yang diposisikan pada batas elemen yang tidak akan dilampaui oleh [XPathNavigator](../) saat mencari elemen berikutnya. |

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil dipindahkan; selainnya, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) metode

Memindahkan [XPathNavigator](../) ke elemen berikutnya dengan XPathNodeType yang ditentukan dalam urutan dokumen.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType elemen. XPathNodeType tidak dapat berupa [XPathNodeType::Attribute](../../xpathnodetype/) atau [XPathNodeType::Namespace](../../xpathnodetype/). |

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil dipindahkan; selainnya, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) metode

Memindahkan [XPathNavigator](../) ke elemen berikutnya dengan XPathNodeType yang ditentukan, ke batas yang ditentukan, dalam urutan dokumen.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType elemen. XPathNodeType tidak dapat berupa [XPathNodeType::Attribute](../../xpathnodetype/) atau [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objek [XPathNavigator](../) yang diposisikan pada batas elemen yang tidak akan dilampaui oleh [XPathNavigator](../) saat mencari elemen berikutnya. |

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil dipindahkan; selainnya, **false**.

## Lihat Juga

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [XPathNavigator](../)
* Ruang Nama [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)