---
title: AppendAllLines()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan string dari koleksi string yang ditentukan ke file yang ditentukan menggunakan enkoding yang ditentukan dengan menulis setiap string pada baris baru. Jika file yang ditentukan tidak ada, file tersebut dibuat. File ditutup setelah menulis semua string.
type: docs
weight: 1
url: /id/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) metode

Menambahkan string dari koleksi string yang ditentukan ke file yang ditentukan menggunakan enkoding yang ditentukan dengan menulis setiap string pada baris baru. Jika file yang ditentukan tidak ada, file tersebut akan dibuat. File ditutup setelah menulis semua string.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file untuk menambahkan string |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | String yang akan ditulis ke file |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding karakter yang akan digunakan |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Kelas [String](../../../system/string/)
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Kelas [File](../)
* Namespace [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)