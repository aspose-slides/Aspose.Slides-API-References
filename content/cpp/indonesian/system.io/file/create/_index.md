---
title: Create()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat file baru (atau menimpa yang ada) dan membukanya untuk akses membaca dan menulis menggunakan ukuran buffer dan opsi yang ditentukan.
type: docs
weight: 53
url: /id/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) metode


Membuat file baru (atau menimpa yang ada) dan membukanya untuk akses membaca dan menulis menggunakan ukuran buffer dan opsi yang ditentukan.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Jalur file untuk dibuat atau ditimpa |
| bufferSize | **int32_t** | Jumlah byte yang di-buffer saat membaca dari dan menulis ke file |
| options | [FileOptions](../../fileoptions/) | Menentukan cara membuat atau menimpa file |

### Nilai Kembali

Pointer bersama ke objek [FileStream](../../filestream/) yang terkait dengan file yang ditentukan

## Lihat Juga

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Kelas [String](../../../system/string/)
* Kelas [File](../)
* Ruang Nama [System::IO](../../)
* Library [Aspose.Slides](../../../)