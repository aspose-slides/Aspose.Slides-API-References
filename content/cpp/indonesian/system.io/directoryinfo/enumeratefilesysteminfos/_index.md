---
title: EnumerateFileSystemInfos()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi enumerable yang berisi semua berkas dan direktori yang berada di dalam direktori yang direpresentasikan oleh objek saat ini.
type: docs
weight: 131
url: /id/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() metode

Mengembalikan koleksi enumerable yang berisi semua berkas dan direktori yang berada di dalam direktori yang direpresentasikan oleh objek saat ini.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) metode

Mencari berkas dan direktori yang memenuhi kriteria pencarian yang ditentukan di dalam direktori yang direpresentasikan oleh objek saat ini.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama berkas dan direktori yang akan dicari |

### Nilai Kembalian

Koleksi enumerable dari shared pointer ke objek [FileSystemInfo](../../filesysteminfo/) yang merepresentasikan berkas dan direktori yang ditemukan yang namanya cocok dengan **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) metode

Mencari berkas dan direktori yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang direpresentasikan oleh objek saat ini maupun di seluruh pohon direktori yang berakar pada direktori yang direpresentasikan oleh objek saat ini.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama berkas dan direktori yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya pada direktori yang direpresentasikan oleh objek saat ini atau pada seluruh pohon direktori yang berakar pada direktori yang direpresentasikan oleh objek saat ini |

### Nilai Kembalian

Koleksi enumerable dari shared pointer ke objek [FileSystemInfo](../../filesysteminfo/) yang merepresentasikan berkas dan direktori yang ditemukan yang namanya cocok dengan **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)