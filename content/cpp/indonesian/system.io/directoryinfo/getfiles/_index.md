---
title: GetFiles()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan array yang berisi shared pointer ke objek FileInfo yang mewakili semua direktori yang terletak di direktori yang direpresentasikan oleh objek saat ini.
type: docs
weight: 157
url: /id/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() metode

Mengembalikan sebuah array yang berisi shared pointer ke objek [FileInfo](../../fileinfo/) yang mewakili semua direktori yang terletak di direktori yang direpresentasikan oleh objek saat ini.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) metode

Mencari file yang memenuhi kriteria pencarian yang ditentukan di direktori yang direpresentasikan oleh objek saat ini.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama file yang akan dicari |

### Nilai Kembalian

Sebuah array berisi shared pointer ke objek [FileInfo](../../fileinfo/) yang mewakili file yang ditemukan yang namanya cocok dengan **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) metode

Mencari file yang memenuhi kriteria pencarian yang ditentukan baik di direktori yang direpresentasikan oleh objek saat ini maupun di seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama file yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya pada direktori yang direpresentasikan oleh objek saat ini atau pada seluruh pohon direktori yang berakar di direktori yang direpresentasikan oleh objek saat ini |

### Nilai Kembalian

Sebuah array berisi shared pointer ke objek [FileInfo](../../fileinfo/) yang mewakili file yang ditemukan yang namanya cocok dengan **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Kelas [DirectoryInfo](../)
* Kelas [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)