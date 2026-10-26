---
title: get_NameTable()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan XmlNameTable yang digunakan untuk perbandingan string yang diatomisasi.
type: docs
weight: 1
url: /id/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() metode

Mengembalikan [XmlNameTable](../../xmlnametable/) yang digunakan untuk perbandingan string yang diatomisasi.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Nilai Kembali

[XmlNameTable](../../xmlnametable/) yang menyimpan semua string yang diatomisasi yang digunakan oleh semua instansi [XmlReader](../../xmlreader/) yang dibuat menggunakan objek [XmlReaderSettings](../) ini. Defaultnya adalah **nullptr**. Instansi [XmlReader](../../xmlreader/) yang dibuat akan menggunakan [NameTable](../../nametable/) kosong baru jika nilai ini **nullptr**.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNameTable](../../xmlnametable/)
* Kelas [XmlReaderSettings](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)