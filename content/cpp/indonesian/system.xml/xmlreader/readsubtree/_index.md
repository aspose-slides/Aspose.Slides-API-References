---
title: ReadSubtree()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah instance XmlReader baru yang dapat digunakan untuk membaca node saat ini, dan semua turunannya.
type: docs
weight: 963
url: /id/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() metode

Mengembalikan sebuah instance [XmlReader](../) baru yang dapat digunakan untuk membaca node saat ini, dan semua turunannya.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### Nilai Kembalian

Sebuah instance pembaca XML baru diatur ke [ReadState::Initial](../../readstate/). Memanggil metode [XmlReader::Read](../read/) menempatkan pembaca baru pada node yang menjadi node saat ini sebelum pemanggilan metode [XmlReader::ReadSubtree](./).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlReader](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)