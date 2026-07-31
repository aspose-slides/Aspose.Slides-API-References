---
title: get_OldValue()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai asli node.
type: docs
weight: 53
url: /id/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() metode

Mengembalikan nilai asli node.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```

### Nilai Kembali

Nilai asli node. Metode ini mengembalikan **nullptr** jika node bukan atribut maupun node teks, atau jika node sedang disisipkan. Jika dipanggil dalam acara **XmlDocument::NodeChanging**, **get_OldValue** mengembalikan nilai saat ini dari node yang akan diganti jika perubahan berhasil. Jika dipanggil dalam acara **XmlDocument::NodeChanged**, **get_OldValue** mengembalikan nilai node sebelum perubahan.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)