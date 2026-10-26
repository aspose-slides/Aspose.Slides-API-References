---
title: EnumerateDirectories()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi yang dapat diiterasi berisi semua direktori yang terletak di dalam direktori yang direpresentasikan oleh objek saat ini.
type: docs
weight: 105
url: /id/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() metode

Mengembalikan koleksi yang dapat diiterasi berisi semua direktori yang terletak di direktori yang direpresentasikan oleh objek saat ini.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) metode

Mencari direktori yang memenuhi kriteria pencarian yang ditentukan di dalam direktori yang direpresentasikan oleh objek saat ini.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Polanya nama direktori yang akan dicari |

### Nilai Kembalian

Koleksi yang dapat diiterasi berupa pointer bersama ke objek [DirectoryInfo](../) yang mewakili direktori yang ditemukan dengan nama yang cocok **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) metode

Mencari direktori yang memenuhi kriteria pencarian yang ditentukan, baik di dalam direktori yang direpresentasikan oleh objek saat ini maupun di seluruh pohon direktori yang berakar pada direktori yang direpresentasikan oleh objek saat ini.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Polanya nama direktori yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya di dalam direktori yang direpresentasikan oleh objek saat ini atau di seluruh pohon direktori yang berakar pada direktori yang direpresentasikan oleh objek saat ini |

### Nilai Kembalian

Koleksi yang dapat diiterasi berupa pointer bersama ke objek [DirectoryInfo](../) yang mewakili direktori yang ditemukan dengan nama yang cocok **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)