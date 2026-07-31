---
title: BinaryReader()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance dari kelas BinaryReader yang membaca data dari aliran yang ditentukan menggunakan enkoding UTF-8.
type: docs
weight: 1
url: /id/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) konstruktor


Membuat sebuah instance dari kelas [BinaryReader](../) yang membaca data dari aliran yang ditentukan menggunakan enkoding UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Aliran masuk |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) konstruktor


Membuat sebuah instance dari kelas [BinaryReader](../) yang membaca data dari aliran yang ditentukan menggunakan enkoding yang ditentukan.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Aliran masuk |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Enkoding yang akan digunakan |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) konstruktor


Membuat sebuah instance dari kelas [BinaryReader](../) yang membaca data dari aliran yang ditentukan menggunakan enkoding yang ditentukan.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Aliran masuk |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Enkoding yang akan digunakan |
| leaveOpen | **bool** | Menentukan apakah aliran **input** harus tetap terbuka (true) setelah objek saat ini dibuang atau tidak (false) |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Stream](../../stream/)
* Kelas [BinaryReader](../)
* Kelas [Encoding](../../../system.text/encoding/)
* Ruang Nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)