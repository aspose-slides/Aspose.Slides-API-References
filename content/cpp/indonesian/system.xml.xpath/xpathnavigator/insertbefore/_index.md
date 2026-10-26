---
title: InsertBefore()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek XmlWriter yang digunakan untuk membuat node saudara baru sebelum node yang saat ini dipilih.
type: docs
weight: 911
url: /id/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() method

Mengembalikan objek [XmlWriter](../../../system.xml/xmlwriter/) yang digunakan untuk membuat node saudara baru sebelum node yang saat ini dipilih.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### Nilai Kembalian

Sebuah objek [XmlWriter](../../../system.xml/xmlwriter/) yang digunakan untuk membuat node saudara baru sebelum node yang saat ini dipilih.

## XPathNavigator::InsertBefore(String) method

Membuat node saudara baru sebelum node yang saat ini dipilih menggunakan string XML yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | String data XML untuk node saudara baru. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) method

Membuat node saudara baru sebelum node yang saat ini dipilih menggunakan isi XML dari objek [XmlReader](../../../system.xml/xmlreader/) yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Sebuah objek [XmlReader](../../../system.xml/xmlreader/) yang diposisikan pada data XML untuk node saudara baru. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) method

Membuat node saudara baru sebelum node yang saat ini dipilih menggunakan node dalam [XPathNavigator](../) yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Sebuah objek [XPathNavigator](../) yang diposisikan pada node yang akan ditambahkan sebagai node saudara baru. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)