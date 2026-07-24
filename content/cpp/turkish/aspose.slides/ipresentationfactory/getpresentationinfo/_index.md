---
title: GetPresentationInfo()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen dosyada bulunan sunum hakkında bilgi alır.
type: docs
weight: 14
url: /tr/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) metot

Belirtilen dosyada bulunan sunum hakkında bilgi alır.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| dosya | [System::String](../../../system/string/) | [Presentation](../../presentation/) dosya. |

### Dönüş Değeri

[Presentation](../../presentation/) bilgi

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) metot

Belirtilen akışta bulunan sunum hakkında bilgi alır.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| akış | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) akış. |

### Dönüş Değeri

[Presentation](../../presentation/) bilgi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPresentationInfo](../../ipresentationinfo/)
* Sınıf [String](../../../system/string/)
* Sınıf [IPresentationFactory](../)
* Sınıf [Stream](../../../system.io/stream/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)