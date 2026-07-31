---
title: InsertAfter()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek XmlWriter yang digunakan untuk membuat node saudara baru setelah node yang saat ini dipilih.
type: docs
weight: 898
url: /id/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() metode

Mengembalikan sebuah objek [XmlWriter](../../../system.xml/xmlwriter/) yang digunakan untuk membuat node saudara baru setelah node yang saat ini dipilih.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Nilai Kembalian

Sebuah objek [XmlWriter](../../../system.xml/xmlwriter/) yang digunakan untuk membuat node saudara baru setelah node yang saat ini dipilih.

## XPathNavigator::InsertAfter(String) metode

Membuat node saudara baru setelah node yang saat ini dipilih menggunakan string XML yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | String data XML untuk node saudara baru. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) metode

Membuat node saudara baru setelah node yang saat ini dipilih menggunakan konten XML dari objek [XmlReader](../../../system.xml/xmlreader/) yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Sebuah objek [XmlReader](../../../system.xml/xmlreader/) yang diposisikan pada data XML untuk node saudara baru. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) metode

Membuat node saudara baru setelah node yang saat ini dipilih menggunakan node dalam objek [XPathNavigator](../) yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Sebuah objek [XPathNavigator](../) yang diposisikan pada node yang akan ditambahkan sebagai node saudara baru. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlWriter](../../../system.xml/xmlwriter/)
* Kelas [XPathNavigator](../)
* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../../../system.xml/xmlreader/)
* Ruang Nama [System::Xml::XPath](../../)
* Perpustakaan [Aspose.Slides](../../../)