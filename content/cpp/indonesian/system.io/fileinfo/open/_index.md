---
title: Open()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuka file yang diwakili oleh objek saat ini dalam mode yang ditentukan untuk membaca dan menulis tanpa berbagi.
type: docs
weight: 183
url: /id/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) metode

Membuka file yang diwakili oleh objek saat ini dalam mode yang ditentukan untuk membaca dan menulis tanpa berbagi.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Menentukan mode di mana file akan dibuka |

### Nilai Kembali

Objek [FileStream](../../filestream/) yang terkait dengan file yang diwakili oleh objek saat ini

## FileInfo::Open(FileMode, FileAccess) metode

Membuka file yang diwakili oleh objek saat ini dalam mode yang ditentukan, dengan tipe akses yang ditentukan dan tanpa berbagi.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Menentukan mode di mana file akan dibuka |
| access | [FileAccess](../../fileaccess/) | Tipe akses yang diminta |

### Nilai Kembali

Objek [FileStream](../../filestream/) yang terkait dengan file yang diwakili oleh objek saat ini

## FileInfo::Open(FileMode, FileAccess, FileShare) metode

Membuka file yang diwakili oleh objek saat ini dalam mode yang ditentukan, dengan tipe akses yang ditentukan dan opsi berbagi.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Menentukan mode di mana file akan dibuka |
| access | [FileAccess](../../fileaccess/) | Tipe akses yang diminta |
| share | [FileShare](../../fileshare/) | Tipe akses yang dimiliki oleh objek [FileStream](../../filestream/) lain ke file yang dibuka |

### Nilai Kembali

Objek [FileStream](../../filestream/) yang terkait dengan file yang diwakili oleh objek saat ini

## Lihat Juga

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)