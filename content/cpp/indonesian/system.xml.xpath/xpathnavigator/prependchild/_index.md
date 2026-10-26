---
title: PrependChild()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek XmlWriter yang digunakan untuk membuat node anak baru di awal daftar node anak dari node saat ini.
type: docs
weight: 872
url: /id/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() metode


Mengembalikan objek [XmlWriter](../../../system.xml/xmlwriter/) yang digunakan untuk membuat node anak baru di awal daftar node anak dari node saat ini.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```


### Nilai Kembali

Objek [XmlWriter](../../../system.xml/xmlwriter/) yang digunakan untuk membuat node anak baru di awal daftar node anak dari node saat ini.

## XPathNavigator::PrependChild(String) metode


Membuat node anak baru di awal daftar node anak dari node saat ini menggunakan string XML yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | String data XML untuk node anak baru. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) metode


Membuat node anak baru di awal daftar node anak dari node saat ini menggunakan isi XML dari objek [XmlReader](../../../system.xml/xmlreader/) yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Objek [XmlReader](../../../system.xml/xmlreader/) yang diposisikan pada data XML untuk node anak baru. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) metode


Membuat node anak baru di awal daftar node anak dari node saat ini menggunakan node dalam objek [XPathNavigator](../) yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objek [XPathNavigator](../) yang diposisikan pada node yang akan ditambahkan sebagai node anak baru. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlWriter](../../../system.xml/xmlwriter/)
* Kelas [XPathNavigator](../)
* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)