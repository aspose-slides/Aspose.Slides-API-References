---
title: GetPresentationInfo()
second_title: Aspose.Slides for C++ API Referansı
description: Dosyadan yeni PresentationInfo nesnesi oluşturur ve sunumu buna bağlar.
type: docs
weight: 27
url: /tr/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) yöntemi

Dosyadan yeni [PresentationInfo](../../presentationinfo/) nesnesi oluşturur ve sunumu buna bağlar.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) dosyası. |

### Dönüş Değeri

[Presentation](../../presentation/) bilgi sunuma bağlanmış.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) yöntemi

Akıştan yeni [PresentationInfo](../../presentationinfo/) nesnesi oluşturur ve sunumu buna bağlar. Belirtilen akıştaki sunum hakkında bilgi alır.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) akışı. |

### Dönüş Değeri

[Presentation](../../presentation/) bilgi sunuma bağlanmış.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPresentationInfo](../../ipresentationinfo/)
* Sınıf [String](../../../system/string/)
* Sınıf [PresentationFactory](../)
* Sınıf [Stream](../../../system.io/stream/)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)