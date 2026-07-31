---
title: GetDirectories()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sebuah array yang berisi shared pointer ke objek DirectoryInfo yang mewakili semua direktori yang berada di dalam direktori yang direpresentasikan oleh objek saat ini.
type: docs
weight: 144
url: /id/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() metode


Mengembalikan sebuah array berisi shared pointer ke objek [DirectoryInfo](../) yang mewakili semua direktori yang berada di dalam direktori yang direpresentasikan oleh objek saat ini.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) metode


Mencari direktori yang memenuhi kriteria pencarian yang ditentukan di dalam direktori yang direpresentasikan oleh objek saat ini.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama direktori yang akan dicari |

### Nilai Kembali

Sebuah array berisi shared pointer ke objek [DirectoryInfo](../) yang mewakili direktori yang ditemukan dengan nama yang cocok dengan **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) metode


Mencari direktori yang memenuhi kriteria pencarian yang ditentukan baik di dalam direktori yang direpresentasikan oleh objek saat ini maupun di seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama direktori yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya di direktori yang direpresentasikan oleh objek saat ini atau di seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini |

### Nilai Kembali

Sebuah array berisi shared pointer ke objek [DirectoryInfo](../) yang mewakili direktori yang ditemukan dengan nama yang cocok dengan **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)