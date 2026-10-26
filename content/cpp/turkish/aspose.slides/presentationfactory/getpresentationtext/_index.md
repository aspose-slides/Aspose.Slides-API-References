---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API Referansı
description: Slaytlardan ham metni alır
type: docs
weight: 53
url: /tr/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metodu

Slaytlardan ham metni alır

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Giriş dosyası |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Çıkarma modu |

### Dönüş Değeri

Ham slayt metnini temsil eden SlideText dizisini içeren [PresentationText](../../presentationtext/) örneği

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metodu

Slaytlardan ham metni alır

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Giriş akışı |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Çıkarma modu |

### Dönüş Değeri

Ham slayt metnini temsil eden SlideText dizisini içeren [PresentationText](../../presentationtext/) örneği

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metodu

Slaytlardan ham metni alır

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Giriş akışı |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Çıkarma modu |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Yükleme seçenekleri |

### Dönüş Değeri

Ham slayt metnini temsil eden SlideText dizisini içeren [PresentationText](../../presentationtext/) örneği

## İlgili

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPresentationText](../../ipresentationtext/)
* Sınıf [String](../../../system/string/)
* Sınıf [PresentationFactory](../)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [ILoadOptions](../../iloadoptions/)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)