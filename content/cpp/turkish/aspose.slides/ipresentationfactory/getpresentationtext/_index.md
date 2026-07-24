---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API Referansı
description: Slaytlardan ham metni alır
type: docs
weight: 40
url: /tr/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metodu

Slaytlardan ham metni alır

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Girdi dosyası |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Çıkarma modu |

### Dönüş Değeri

[PresentationText](../../presentationtext/) örneği, ham slayt metnini temsil eden SlideText dizisini içerir

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metodu

Slaytlardan ham metni alır

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Girdi akışı |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Çıkarma modu |

### Dönüş Değeri

[PresentationText](../../presentationtext/) örneği, ham slayt metnini temsil eden SlideText dizisini içerir

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metodu

Slaytlardan ham metni alır

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Girdi akışı |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Çıkarma modu |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Yükleme seçenekleri |

### Dönüş Değeri

[PresentationText](../../presentationtext/) örneği, ham slayt metnini temsil eden SlideText dizisini içerir

## Ayrıca Bakınız

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPresentationText](../../ipresentationtext/)
* Sınıf [String](../../../system/string/)
* Sınıf [IPresentationFactory](../)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [ILoadOptions](../../iloadoptions/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)