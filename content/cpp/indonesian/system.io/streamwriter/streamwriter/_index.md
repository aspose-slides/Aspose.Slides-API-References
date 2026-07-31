---
title: StreamWriter()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance objek StreamWriter yang menulis karakter ke aliran dasar yang ditentukan menggunakan enkoding UTF-8 dan buffer dengan ukuran default 1024 byte.
type: docs
weight: 1
url: /id/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) konstruktor


Membuat sebuah instance objek [StreamWriter](../) yang menulis karakter ke aliran dasar yang ditentukan menggunakan enkoding UTF-8 dan buffer dengan ukuran default 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Aliran dasar yang akan ditulis karakternya |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) konstruktor


Membuat sebuah instance objek [StreamWriter](../) yang menulis karakter ke aliran dasar yang ditentukan menggunakan enkoding yang ditentukan dan buffer dengan ukuran default 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Aliran dasar yang akan ditulis karakternya |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) konstruktor


Membuat sebuah instance objek [StreamWriter](../) yang menulis karakter ke aliran dasar yang ditentukan menggunakan enkoding yang ditentukan dan buffer dengan ukuran yang ditentukan. Sebuah parameter menentukan apakah aliran dasar harus ditutup ketika objek [StreamWriter](../) dibuang.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Aliran dasar yang akan ditulis karakternya |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |
| buffer_size | int | Ukuran minimum buffer dalam byte |
| leave_open | **bool** | Menentukan apakah aliran dasar harus tetap terbuka setelah objek [StreamWriter](../) saat ini dibuang |

## StreamWriter::StreamWriter(const String\&) konstruktor


Membuat sebuah instance objek [StreamWriter](../) yang menulis karakter ke file yang ditentukan menggunakan enkoding UTF-8 dan buffer dengan ukuran default 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan ditulis karakternya |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) konstruktor


Membuat sebuah instance objek [StreamWriter](../) yang menulis karakter ke file yang ditentukan menggunakan enkoding yang ditentukan dan buffer dengan ukuran default 1024 byte. Sebuah parameter menentukan apakah data harus ditambahkan ke file atau file harus ditimpa.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan ditulis karakternya |
| append | **bool** | Menentukan apakah data harus ditambahkan ke file yang ditentukan (true) atau file harus ditimpa (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) konstruktor


Membuat sebuah instance objek [StreamWriter](../) yang menulis karakter ke file yang ditentukan menggunakan enkoding yang ditentukan dan ukuran buffer. Sebuah parameter menentukan apakah data harus ditambahkan ke file atau file harus ditimpa.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan ditulis karakternya |
| append | **bool** | Menentukan apakah data harus ditambahkan ke file yang ditentukan (true) atau file harus ditimpa (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |
| buffer_size | int | Ukuran buffer yang akan digunakan |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)