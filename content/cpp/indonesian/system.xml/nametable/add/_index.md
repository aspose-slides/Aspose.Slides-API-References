---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menganatomkan string yang ditentukan dan menambahkannya ke NameTable.
type: docs
weight: 14
url: /id/system.xml/nametable/add/
---
## NameTable::Add(const String\&) metode


Menganatomkan string yang ditentukan dan menambahkannya ke [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | String yang akan ditambahkan. |

### Nilai Kembali

String yang telah diatomkan atau string yang sudah ada jika sudah ada di [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metode


Menganatomkan string yang ditentukan dan menambahkannya ke [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Array karakter yang berisi string yang akan ditambahkan. |
| start | **int32_t** | Indeks berbasis nol ke dalam array yang menentukan karakter pertama dari string. |
| len | **int32_t** | Jumlah karakter dalam string. |

### Nilai Kembali

String yang telah diatomkan atau string yang sudah ada jika sudah ada di [NameTable](../). Jika **len** bernilai nol, [String::Empty](../../../system/string/empty/) dikembalikan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [NameTable](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)