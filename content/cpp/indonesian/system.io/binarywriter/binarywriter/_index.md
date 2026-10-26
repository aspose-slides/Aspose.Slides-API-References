---
title: BinaryWriter()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance kelas BinaryWriter yang menulis data ke stream yang ditentukan menggunakan encoding yang ditentukan.
type: docs
weight: 1
url: /id/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) constructor


Membuat sebuah instance kelas [BinaryWriter](../) yang menulis data ke stream yang ditentukan menggunakan encoding yang ditentukan.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aliran output |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Encoding yang akan digunakan |
| leaveopen | **bool** | Menentukan apakah **stream** harus tetap terbuka (true) setelah objek saat ini dibuang atau tidak (false) |

## Lihat Juga

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Kelas [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)