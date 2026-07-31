---
title: GetPresentationText()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil teks mentah dari slide
type: docs
weight: 53
url: /id/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method


Mengambil teks mentah dari slide

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | File masukan |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode ekstraksi |

### Nilai Kembalian

Instance dari [PresentationText](../../presentationtext/) yang berisi array SlideText yang mewakili teks mentah slide

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method


Mengambil teks mentah dari slide

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream masukan |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode ekstraksi |

### Nilai Kembalian

Instance dari [PresentationText](../../presentationtext/) yang berisi array SlideText yang mewakili teks mentah slide

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method


Mengambil teks mentah dari slide

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream masukan |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode ekstraksi |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opsi muat |

### Nilai Kembalian

Instance dari [PresentationText](../../presentationtext/) yang berisi array SlideText yang mewakili teks mentah slide

## Lihat Juga

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPresentationText](../../ipresentationtext/)
* Kelas [String](../../../system/string/)
* Kelas [PresentationFactory](../)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)