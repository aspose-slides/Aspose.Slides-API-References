---
title: ReadAllLines()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten file teks yang ditentukan baris demi baris ke dalam array string menggunakan pengkodean karakter yang ditentukan.
type: docs
weight: 300
url: /id/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) metode

Membaca konten file teks yang ditentukan baris demi baris ke dalam array string menggunakan pengkodean karakter yang ditentukan.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan dibaca |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Pengkodean karakter yang akan digunakan |

### Nilai Kembali

Array string di mana setiap elemennya mewakili satu baris dari file yang ditentukan

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Kelas [String](../../../system/string/)
* Kelas [File](../)
* Ruang Nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)