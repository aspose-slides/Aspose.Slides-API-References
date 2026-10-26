---
title: CreateFileStreamWrapper()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat FileStream dengan jalur yang ditentukan dan mode pembuatan.
type: docs
weight: 14
url: /id/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) metode

Membuat FileStream dengan jalur yang ditentukan dan mode pembuatan.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nama file [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Mode file [System::IO::FileMode](../../../system.io/filemode/) |

### Nilai Kembali

Pembungkus aliran untuk antarmuka COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) metode

Membuat FileStream dengan jalur yang ditentukan, mode pembuatan, dan izin baca/menulis.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nama file [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Mode file [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Akses file [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Nilai Kembali

Pembungkus aliran untuk antarmuka COM [IStreamWrapper](../../istreamwrapper/)

## Lihat Juga

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IStreamWrapper](../../istreamwrapper/)
* Kelas [String](../../../system/string/)
* Kelas [IStreamWrapperFactory](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)