---
title: Equals()
second_title: Aspose.Slides for C++ API Referansı
description: İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönüş değeri, slaytın yapısı ve statik içeriği temel alınarak hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, benzersiz tanımlayıcı değerlerini (ör. SlideId) ve dinamik içeriği (ör. Date Placeholder içindeki geçerli tarih değeri) dikkate almaz.
type: docs
weight: 183
url: /tr/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) metodu

İki [IBaseSlide](../) örneğinin eşit olup olmadığını belirler. Dönüş değeri, slaytın yapısı ve statik içeriği temel alınarak hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, benzersiz tanımlayıcı değerlerini (ör. SlideId) ve dinamik içeriği (ör. Date [Placeholder](../../placeholder/) içinde mevcut tarih değeri) dikkate almaz.

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | [IBaseSlide](../), mevcut [IBaseSlide](../) ile karşılaştırılacak. |

### Dönüş Değeri

**true** eğer belirtilen [IBaseSlide](../) mevcut [IBaseSlide](../) ile eşitse; aksi takdirde, **false**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IBaseSlide](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)