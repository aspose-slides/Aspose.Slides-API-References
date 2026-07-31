---
title: GetPresentationText()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil teks mentah dari slide
type: docs
weight: 40
url: /id/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metode


Mengambil teks mentah dari slide

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Berkas masukan |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode ekstraksi |

### Nilai Kembali

Instansi [PresentationText](../../presentationtext/) yang berisi array SlideText yang mewakili teks mentah slide

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metode


Mengambil teks mentah dari slide

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream masukan |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode ekstraksi |

### Nilai Kembali

Instansi [PresentationText](../../presentationtext/) yang berisi array SlideText yang mewakili teks mentah slide

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metode


Mengambil teks mentah dari slide

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream masukan |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode ekstraksi |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opsi pemuatan |

### Nilai Kembali

Instansi [PresentationText](../../presentationtext/) yang berisi array SlideText yang mewakili teks mentah slide

## Lihat Juga

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)