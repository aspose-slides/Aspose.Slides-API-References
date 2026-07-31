---
title: Open()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuka file yang ditentukan dalam mode yang ditentukan untuk membaca dan menulis tanpa berbagi.
type: docs
weight: 235
url: /id/system.io/file/open/
---
## File::Open(const String\&, FileMode) metode


Membuka file yang ditentukan dalam mode yang ditentukan untuk membaca dan menulis tanpa berbagi.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan dibuka |
| mode | [FileMode](../../filemode/) | Menentukan mode di mana file akan dibuka |

### Nilai Kembalian

Objek [FileStream](../../filestream/) yang terkait dengan file yang dibuka

## File::Open(const String\&, FileMode, FileAccess, FileShare) metode


Membuka file yang ditentukan dalam mode yang ditentukan, dengan tipe akses dan opsi berbagi yang ditentukan.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file yang akan dibuka |
| mode | [FileMode](../../filemode/) | Menentukan mode di mana file akan dibuka |
| access | [FileAccess](../../fileaccess/) | Jenis akses yang diminta |
| share | [FileShare](../../fileshare/) | Jenis akses yang dimiliki objek [FileStream](../../filestream/) lain terhadap file yang dibuka |

### Nilai Kembalian

Objek [FileStream](../../filestream/) yang terkait dengan file yang dibuka

## Lihat Juga

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)