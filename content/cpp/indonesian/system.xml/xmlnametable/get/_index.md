---
title: Get()
second_title: Aspose.Slides for C++ Referensi API
description: Saat ditimpa dalam kelas turunan, memperoleh string yang diatomisasi yang berisi karakter yang sama dengan rentang karakter yang ditentukan dalam array yang diberikan.
type: docs
weight: 1
url: /id/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metode

Saat ditimpa dalam kelas turunan, memperoleh string yang diatomisasi yang berisi karakter yang sama dengan rentang karakter yang ditentukan dalam array yang diberikan.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Array karakter yang berisi nama yang akan dicari. |
| offset | **int32_t** | Indeks berbasis nol ke dalam array yang menentukan karakter pertama dari nama. |
| length | **int32_t** | Jumlah karakter dalam nama. |

### Nilai Kembali

String yang diatomisasi atau **nullptr** jika string belum diatomisasi. Jika **length** bernilai nol, [String::Empty](../../../system/string/empty/) dikembalikan.

## XmlNameTable::Get(const String\&) metode

Saat ditimpa dalam kelas turunan, memperoleh string yang diatomisasi yang berisi nilai yang sama dengan string yang ditentukan.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Nama yang akan dicari. |

### Nilai Kembali

String yang diatomisasi atau **nullptr** jika string belum diatomisasi.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)