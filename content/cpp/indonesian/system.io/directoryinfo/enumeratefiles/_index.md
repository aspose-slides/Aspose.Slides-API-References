---
title: EnumerateFiles()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi yang dapat diiterasi yang berisi semua file yang terletak di direktori yang diwakili oleh objek saat ini.
type: docs
weight: 118
url: /id/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() metode

Mengembalikan koleksi yang dapat diiterasi yang berisi semua file yang terletak di direktori yang diwakili oleh objek saat ini.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) metode

Mencari file yang memenuhi kriteria pencarian yang ditentukan di direktori yang diwakili oleh objek saat ini.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama file yang akan dicari |

### Nilai Kembali

Koleksi yang dapat diiterasi berupa shared pointer ke objek [FileInfo](../../fileinfo/) yang mewakili file yang ditemukan dengan nama yang cocok dengan **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) metode

Mencari file yang memenuhi kriteria pencarian yang ditentukan, baik di direktori yang diwakili oleh objek saat ini maupun di seluruh pohon direktori yang berakar di direktori yang diwakili oleh objek saat ini.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Pola nama file yang akan dicari |
| searchOption | [SearchOption](../../searchoption/) | Menentukan apakah pencarian harus dilakukan hanya di direktori yang diwakili oleh objek saat ini atau di seluruh pohon direktori yang berakar di direktori yang diwakili oleh objek saat ini |

### Nilai Kembali

Koleksi yang dapat diiterasi berupa shared pointer ke objek [FileInfo](../../fileinfo/) yang mewakili file yang ditemukan dengan nama yang cocok dengan **searchPattern**

## Lihat Juga

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)