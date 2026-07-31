---
title: ReadElementString()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode XmlReader::ReadElementContentAsString sebagai gantinya, karena menyediakan cara yang lebih langsung untuk menangani operasi ini."
type: docs
weight: 859
url: /id/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() metode

Membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) sebagai gantinya, karena menyediakan cara yang lebih langsung untuk menangani operasi ini.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Nilai Kembali

Teks yang terdapat dalam elemen yang dibaca. String kosong jika elemen tersebut kosong.

## XmlReader::ReadElementString(String) metode

Memeriksa bahwa nilai [XmlReader::get_Name](../get_name/) dari elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) sebagai gantinya, karena menyediakan cara yang lebih langsung untuk menangani operasi ini.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama yang akan diperiksa. |

### Nilai Kembali

Teks yang terdapat dalam elemen yang dibaca. String kosong jika elemen tersebut kosong.

## XmlReader::ReadElementString(String, String) metode

Memeriksa bahwa nilai [XmlReader::get_LocalName](../get_localname/) dan [XmlReader::get_NamespaceURI](../get_namespaceuri/) dari elemen yang ditemukan cocok dengan string yang diberikan sebelum membaca elemen yang hanya berisi teks. Namun, disarankan untuk menggunakan metode [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) sebagai gantinya, karena menyediakan cara yang lebih langsung untuk menangani operasi ini.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Nama lokal yang akan diperiksa. |
| ns | [String](../../../system/string/) | URI ruang nama yang akan diperiksa. |

### Nilai Kembali

Teks yang terdapat dalam elemen yang dibaca. String kosong jika elemen tersebut kosong.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)