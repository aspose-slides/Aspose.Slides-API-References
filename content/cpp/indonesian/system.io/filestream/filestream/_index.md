---
title: FileStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance baru dari kelas FileStream dan menginisialisasinya dengan parameter yang ditentukan.
type: docs
weight: 1
url: /id/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) konstruktor


Membuat instance baru dari kelas [FileStream](../) dan menginisialisasinya dengan parameter yang ditentukan.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan dibuka. |
| mode | [FileMode](../../filemode/) | Menentukan mode untuk membuka file. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) konstruktor


Membuat instance baru dari kelas [FileStream](../) dan menginisialisasinya dengan parameter yang ditentukan.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan dibuka. |
| mode | [FileMode](../../filemode/) | Menentukan mode untuk membuka file. |
| access | [FileAccess](../../fileaccess/) | Tipe akses yang diminta. |
| share | [FileShare](../../fileshare/) | Tipe akses yang dimiliki objek [FileStream](../) lain terhadap file yang dibuka. |
| buffer_size | **int32_t** | Jumlah byte yang di-buffer selama operasi baca dan tulis. |
| options | [FileOptions](../../fileoptions/) | Opsi tambahan. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) konstruktor


Membuat instance baru dari kelas [FileStream](../) dan menginisialisasinya dengan parameter yang ditentukan.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan dibuka. |
| mode | [FileMode](../../filemode/) | Menentukan mode untuk membuka file. |
| access | [FileAccess](../../fileaccess/) | Tipe akses yang diminta. |
| share | [FileShare](../../fileshare/) | Tipe akses yang dimiliki objek [FileStream](../) lain terhadap file yang dibuka. |
| buffer_size | **int32_t** | Jumlah byte yang di-buffer selama operasi baca dan tulis. |
| useAsync | **bool** | Menentukan apakah akan menggunakan I/O asinkron atau I/O sinkron. |
## Keterangan



Sistem operasi yang mendasari mungkin tidak mendukung I/O asinkron. 

## FileStream::FileStream(const FileStream\&) konstruktor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Lihat Juga

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Kelas [String](../../../system/string/)
* Kelas [FileStream](../)
* Ruang Nama [System::IO](../../)
* Perpustakaan [Aspose.Slides](../../../)