---
title: Replace()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengganti isi file tujuan yang ditentukan dengan file yang diwakili oleh objek FileInfo saat ini dan membuat cadangan file yang diganti.
type: docs
weight: 131
url: /id/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) metode


Mengganti isi file tujuan yang ditentukan dengan file yang diwakili oleh objek [FileInfo](../) saat ini dan membuat cadangan file yang diganti.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Nama file yang akan diganti |
| destinationBackupFileName | const [String](../../../system/string/)\& | Nama file cadangan |

### Nilai Kembali

Objek FileInfor yang mewakili file yang ditunjuk oleh **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) metode


Mengganti isi file tujuan yang ditentukan dengan file yang diwakili oleh objek [FileInfo](../) saat ini dan membuat cadangan file yang diganti.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Nama file yang akan diganti |
| destinationBackupFileName | const [String](../../../system/string/)\& | Nama file cadangan |
| ignoreMetadataErrors | **bool** | Menentukan apakah kesalahan penggabungan dari file yang diganti ke file pengganti harus diabaikan (true) atau tidak (false) |

### Nilai Kembali

Objek FileInfor yang mewakili file yang ditunjuk oleh **destinationFileName**

## Lihat Juga

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Kelas [String](../../../system/string/)
* Kelas [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)