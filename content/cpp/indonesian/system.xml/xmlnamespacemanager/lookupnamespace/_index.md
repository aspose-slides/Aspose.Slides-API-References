---
title: LookupNamespace()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan URI ruang nama untuk prefiks yang ditentukan.
type: docs
weight: 118
url: /id/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) metode


Mengembalikan URI ruang nama untuk prefiks yang ditentukan.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks yang URI ruang namanya ingin Anda selesaikan. Untuk mencocokkan ruang nama default, berikan [String::Empty](../../../system/string/empty/). |

### Nilai Kembalian

URI ruang nama untuk **prefix** atau **nullptr** jika tidak ada ruang nama yang dipetakan. String yang dikembalikan telah diatomisasi. Untuk informasi lebih lanjut tentang string yang diatomisasi, lihat kelas [XmlNameTable](../../xmlnametable/).

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNamespaceManager](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)