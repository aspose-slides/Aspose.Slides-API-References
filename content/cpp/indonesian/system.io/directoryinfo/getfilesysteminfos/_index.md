---
title: GetFileSystemInfos()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah array yang berisi shared pointers ke objek FileSystemInfo yang mewakili semua file dan direktori yang berada di dalam direktori yang direpresentasikan oleh objek saat ini.
type: docs
weight: 170
url: /id/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() metode

Mengembalikan sebuah array yang berisi shared pointers ke objek [FileSystemInfo](../../filesysteminfo/) yang mewakili semua file dan direktori yang berada di dalam direktori yang direpresentasikan oleh objek saat ini.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) metode

Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan di dalam direktori yang direpresentasikan oleh objek saat ini.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama file dan direktori yang akan dicari |

### Nilai Kembali

Sebuah array berisi shared pointers ke objek [FileSystemInfo](../../filesysteminfo/) yang mewakili file dan direktori yang ditemukan dengan nama yang cocok **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) metode

Mencari file dan direktori yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang direpresentasikan oleh objek saat ini maupun di seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama file dan direktori yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya di dalam direktori yang direpresentasikan oleh objek saat ini atau di seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini |

### Nilai Kembali

Sebuah array berisi shared pointers ke objek [FileSystemInfo](../../filesysteminfo/) yang mewakili file dan direktori yang ditemukan dengan nama yang cocok **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Kelas [DirectoryInfo](../)
* Kelas [String](../../../system/string/)
* RuangNama [System::IO](../../)
* Library [Aspose.Slides](../../../)