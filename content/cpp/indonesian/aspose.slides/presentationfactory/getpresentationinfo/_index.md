---
title: GetPresentationInfo()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek PresentationInfo baru dari file dan mengikat presentasi ke objek tersebut.
type: docs
weight: 27
url: /id/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) metode

Membuat objek [PresentationInfo](../../presentationinfo/) baru dari file dan mengikat presentasi ke objek tersebut.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) berkas. |

### Nilai Kembali

[Presentation](../../presentation/) info terikat ke presentasi.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) metode

Membuat objek [PresentationInfo](../../presentationinfo/) baru dari aliran dan mengikat presentasi ke objek tersebut. Mendapatkan info tentang presentasi dalam aliran yang ditentukan.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) aliran. |

### Nilai Kembali

[Presentation](../../presentation/) info terikat ke presentasi.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationInfo](../../ipresentationinfo/)
* Class [String](../../../system/string/)
* Class [PresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)