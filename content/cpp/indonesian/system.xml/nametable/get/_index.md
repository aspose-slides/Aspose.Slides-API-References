---
title: Get()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan string yang telah diatomisasi dengan nilai yang ditentukan.
type: docs
weight: 27
url: /id/system.xml/nametable/get/
---
## NameTable::Get(const String\&) metode

Mengembalikan string yang telah diatomisasi dengan nilai yang ditentukan.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Nama yang akan dicari. |

### Nilai Kembalian

Objek string yang telah diatomisasi atau **nullptr** jika string belum diatomisasi.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metode

Mengembalikan string yang telah diatomisasi yang berisi karakter yang sama dengan rentang karakter yang ditentukan dalam array yang diberikan.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Array karakter yang berisi nama yang akan dicari. |
| start | **int32_t** | Indeks berbasis nol ke dalam array yang menentukan karakter pertama dari nama. |
| len | **int32_t** | Jumlah karakter dalam nama. |

### Nilai Kembalian

String yang telah diatomisasi atau **nullptr** jika string belum diatomisasi. Jika **len** adalah nol, [String::Empty](../../../system/string/empty/) dikembalikan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)