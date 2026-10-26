---
title: ReadLines()
second_title: Aspose.Slides untuk C++ Referensi API
description: Membaca isi file teks yang ditentukan baris per baris menggunakan pengkodean karakter yang ditentukan dan mengembalikan koleksi enumerabel string dimana masing-masing mewakili satu baris dari isi file.
type: docs
weight: 326
url: /id/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) metode

Membaca isi file teks yang ditentukan baris per baris menggunakan pengkodean karakter yang ditentukan dan mengembalikan koleksi enumerabel string dimana masing-masing mewakili satu baris dari isi file.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan dibaca |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Pengkodean karakter yang akan digunakan |

### Nilai Kembali

Mengembalikan koleksi enumerabel string yang mewakili isi file yang ditentukan

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Kelas [String](../../../system/string/)
* Kelas [File](../)
* Ruang nama [System::IO](../../)
* Library [Aspose.Slides](../../../)