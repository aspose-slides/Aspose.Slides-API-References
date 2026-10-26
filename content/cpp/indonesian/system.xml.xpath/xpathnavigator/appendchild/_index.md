---
title: AppendChild()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek XmlWriter yang digunakan untuk membuat satu atau beberapa node anak baru di akhir daftar node anak dari node saat ini.
type: docs
weight: 885
url: /id/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() metode

Mengembalikan objek [XmlWriter](../../../system.xml/xmlwriter/) yang digunakan untuk membuat satu atau beberapa node anak baru di akhir daftar node anak dari node saat ini.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Nilai Kembalian

Objek [XmlWriter](../../../system.xml/xmlwriter/) yang digunakan untuk membuat node anak baru di akhir daftar node anak dari node saat ini.

## XPathNavigator::AppendChild(String) metode

Membuat node anak baru di akhir daftar node anak dari node saat ini menggunakan string data XML yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | String data XML untuk node anak baru. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) metode

Membuat node anak baru di akhir daftar node anak dari node saat ini menggunakan isi XML dari objek [XmlReader](../../../system.xml/xmlreader/) yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Objek [XmlReader](../../../system.xml/xmlreader/) yang diposisikan pada data XML untuk node anak baru. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) metode

Membuat node anak baru di akhir daftar node anak dari node saat ini menggunakan node dalam [XPathNavigator](../) yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Argumen

| Parameter | Tipe | Deskripsi |
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