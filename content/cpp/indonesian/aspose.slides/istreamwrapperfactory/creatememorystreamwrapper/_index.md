---
title: CreateMemoryStreamWrapper()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat pembungkus MemoryStream.
type: docs
weight: 1
url: /id/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() metode

Membuat pembungkus MemoryStream.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### Nilai Kembalian

Pembungkus aliran untuk antarmuka COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) metode

Membuat pembungkus MemoryStream berdasarkan array byte yang ditentukan.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array byte **uint8_t**[] |

### Nilai Kembalian

Pembungkus aliran untuk antarmuka COM [IStreamWrapper](../../istreamwrapper/)

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IStreamWrapper](../../istreamwrapper/)
* Kelas [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)