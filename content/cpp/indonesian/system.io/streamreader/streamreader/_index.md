---
title: StreamReader()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance dari objek StreamReader yang membaca karakter dari stream dasar yang ditentukan menggunakan enkoding UTF-8 dan buffer dengan ukuran default 1024 byte.
type: docs
weight: 1
url: /id/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari stream dasar yang ditentukan menggunakan enkoding UTF-8 dan buffer dengan ukuran default 1024 byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Stream dasar untuk membaca karakter dari |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari stream dasar yang ditentukan menggunakan enkoding UTF-8 dan buffer dengan ukuran default 1024 byte. Sebuah parameter menentukan apakah deteksi byte order mark harus diaktifkan.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Stream dasar untuk membaca karakter dari |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari stream dasar yang ditentukan menggunakan enkoding yang ditentukan dan buffer dengan ukuran default 1024 byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Stream dasar untuk membaca karakter dari |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari stream dasar yang ditentukan menggunakan enkoding yang ditentukan dan buffer dengan ukuran default 1024 byte. Sebuah parameter menentukan apakah deteksi byte order mark harus diaktifkan.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Stream dasar untuk membaca karakter dari |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari stream dasar yang ditentukan menggunakan enkoding yang ditentukan dan buffer dengan ukuran yang ditentukan. Sebuah parameter menentukan apakah deteksi byte order mark harus diaktifkan.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Stream dasar untuk membaca karakter dari |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |
| bufferSize | int | Ukuran minimum buffer dalam byte |

## StreamReader::StreamReader(const System::String\&) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari file yang ditentukan menggunakan enkoding UTF-8 dan buffer dengan ukuran default 4096 byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Jalur file untuk membaca karakter dari |

## StreamReader::StreamReader(const System::String\&, bool) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari file yang ditentukan menggunakan enkoding UTF-8 dan buffer dengan ukuran default 4096 byte. Sebuah parameter menentukan apakah deteksi byte order mark harus diaktifkan.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Jalur file untuk membaca karakter dari |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari file yang ditentukan menggunakan enkoding yang ditentukan dan buffer dengan ukuran default 4096 byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Jalur file untuk membaca karakter dari |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari stream dasar yang ditentukan menggunakan enkoding yang ditentukan dan buffer dengan ukuran default 4096 byte. Sebuah parameter menentukan apakah deteksi byte order mark harus diaktifkan.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Jalur file untuk membaca karakter dari |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor

Membuat sebuah instance dari objek [StreamReader](../) yang membaca karakter dari file yang ditentukan menggunakan enkoding yang ditentukan dan buffer dengan ukuran yang ditentukan. Sebuah parameter menentukan apakah deteksi byte order mark harus diaktifkan.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Jalur file untuk membaca karakter dari |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Enkoding yang akan digunakan |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |
| bufferSize | int | Ukuran minimum buffer dalam byte |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Kelas [Stream](../../stream/)
* Kelas [StreamReader](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::IO](../../)
* Library [Aspose.Slides](../../../)