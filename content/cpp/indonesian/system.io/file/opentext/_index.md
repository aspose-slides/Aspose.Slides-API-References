---
title: OpenText()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuka file yang sudah ada yang ditentukan untuk membaca teks menggunakan enkoding UTF-8 tanpa berbagi.
type: docs
weight: 261
url: /id/system.io/file/opentext/
---
## File::OpenText(const String&, const EncodingPtr&) metode

Membuka file yang sudah ada yang ditentukan untuk membaca teks menggunakan enkoding UTF-8 tanpa berbagi.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Jalur file yang akan dibuka |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | Enkoding karakter yang akan digunakan |

### Nilai Kembalian

Sebuah shared pointer ke objek [StreamWriter](../../streamwriter/) yang terkait dengan file yang dibuka

## Lihat Juga

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Kelas [String](../../../system/string/)
* Kelas [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)