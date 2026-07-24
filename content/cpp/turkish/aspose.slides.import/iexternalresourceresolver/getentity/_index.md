---
title: GetEntity()
second_title: Aspose.Slides for C++ API Referansı
description: Bir URI'yi gerçek kaynağı içeren bir nesneye eşler.
type: docs
weight: 14
url: /tr/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) metodu

Bir URI'yi gerçek kaynağı içeren bir nesneye eşler.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Nesneye ilişkin mutlak URI. |

### Dönüş Değeri

Kaynak akışa konulamazsa [System::IO::Stream](../../../system.io/stream/) nesnesi ya da null.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [String](../../../system/string/)
* Sınıf [IExternalResourceResolver](../)
* İsim Uzayı [Aspose::Slides::Import](../../)
* Kütüphane [Aspose.Slides](../../../)