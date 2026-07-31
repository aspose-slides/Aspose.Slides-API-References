---
title: WriteAllLines()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat file teks baru atau menimpa yang sudah ada dan menulis semua string dari koleksi enumerable string yang ditentukan ke dalamnya, setiap string pada baris baru, menggunakan pengodean yang ditentukan.
type: docs
weight: 456
url: /id/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metode

Membuat file teks baru atau menimpa yang sudah ada dan menulis semua string dari koleksi enumerable string yang ditentukan ke dalamnya, setiap string pada baris baru, menggunakan pengodean yang ditentukan.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | File yang akan dibuat atau ditimpa |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Koleksi enumerable string |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Pengodean karakter yang akan digunakan |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) metode

Membuat file teks baru atau menimpa yang sudah ada dan menulis semua string dari array string yang ditentukan ke dalamnya, setiap string pada baris baru, menggunakan pengodean yang ditentukan.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | File yang akan dibuat atau ditimpa |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Array string |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Pengodean karakter yang akan digunakan |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Kelas [File](../)
* RuangNama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)