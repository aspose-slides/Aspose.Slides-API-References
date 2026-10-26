---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat ditimpa dalam kelas turunan, mengatomkan string yang ditentukan dan menambahkannya ke XmlNameTable.
type: docs
weight: 14
url: /id/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metode

Saat ditimpa dalam kelas turunan, mengatomkan string yang ditentukan dan menambahkannya ke [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Array karakter yang berisi nama yang akan ditambahkan. |
| offset | **int32_t** | Indeks berbasis nol ke dalam array yang menentukan karakter pertama dari nama. |
| length | **int32_t** | Jumlah karakter dalam nama. |

### Nilai Kembalian

String yang diatomkan baru atau yang sudah ada jika sudah ada. Jika panjang nol, [String::Empty](../../../system/string/empty/) dikembalikan.

## XmlNameTable::Add(const String\&) metode

Saat ditimpa dalam kelas turunan, mengatomkan string yang ditentukan dan menambahkannya ke [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Nama yang akan ditambahkan. |

### Nilai Kembalian

String yang diatomkan baru atau yang sudah ada jika sudah ada.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [XmlNameTable](../)
* Ruang nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)