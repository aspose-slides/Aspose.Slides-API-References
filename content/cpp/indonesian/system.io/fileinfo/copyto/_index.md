---
title: CopyTo()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyalin file yang diwakili oleh objek saat ini ke lokasi yang ditentukan. Jika file tujuan sudah ada, penyalinan akan gagal.
type: docs
weight: 105
url: /id/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) metode


Menyalin file yang diwakili oleh objek saat ini ke lokasi yang ditentukan. Jika file tujuan sudah ada, penyalinan gagal.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Nama file tujuan |

### Nilai Kembali

Sebuah objek [FileInfo](../) yang mewakili salinan

## FileInfo::CopyTo(const String\&, bool) metode


Menyalin file yang diwakili oleh objek saat ini ke lokasi yang ditentukan. Sebuah parameter menentukan apakah file tujuan yang ada harus ditimpa.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Nama file tujuan |
| overwrite | **bool** | True jika file tujuan yang ada harus ditimpa, false jika penyalinan harus gagal bila file tujuan sudah ada |

### Nilai Kembali

Sebuah objek [FileInfo](../) yang mewakili salinan

## Lihat Juga

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Kelas [String](../../../system/string/)
* Kelas [FileInfo](../)
* Ruang nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)