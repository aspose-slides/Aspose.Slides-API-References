---
title: BufferedStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek BufferedStream yang membungkus aliran yang ditentukan dan menggunakan buffer sepanjang 4096 byte.
type: docs
weight: 1
url: /id/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) konstruktor

Membuat objek [BufferedStream](../) yang membungkus aliran yang ditentukan dan menggunakan buffer sepanjang 4096 byte.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Objek [Stream](../../stream/) yang mendasari |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) konstruktor

Membuat objek [BufferedStream](../) yang membungkus aliran yang ditentukan dan menggunakan buffer dengan ukuran yang ditentukan.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Objek [Stream](../../stream/) yang mendasari |
| bufferSize | int | Ukuran buffer dalam byte |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Stream](../../stream/)
* Kelas [BufferedStream](../)
* Ruang Nama [System::IO](../../)
* Perpustakaan [Aspose.Slides](../../../)