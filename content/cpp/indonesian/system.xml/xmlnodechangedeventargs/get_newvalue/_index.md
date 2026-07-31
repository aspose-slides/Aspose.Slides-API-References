---
title: get_NewValue()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai baru dari node.
type: docs
weight: 66
url: /id/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() metode


Mengembalikan nilai baru dari node.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### Nilai Kembali

Nilai baru dari node. Metode ini mengembalikan **nullptr** jika node bukan atribut maupun node teks, atau jika node sedang dihapus. Jika dipanggil dalam peristiwa **XmlDocument::NodeChanging**, **get_NewValue** mengembalikan nilai node jika perubahan berhasil. Jika dipanggil dalam peristiwa **XmlDocument::NodeChanged**, **get_NewValue** mengembalikan nilai saat ini dari node.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNodeChangedEventArgs](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)