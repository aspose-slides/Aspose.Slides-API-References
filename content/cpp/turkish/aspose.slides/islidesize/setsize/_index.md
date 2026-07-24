---
title: SetSize()
second_title: Aspose.Slides for C++ API Referansı
description: "Slayt boyutunu türe göre ayarlar ve mevcut içeriği ölçeklendirir. SlideSizeType::Custom dışındaki herhangi bir değer atandığında, seçilen türe göre ISlideSize::get_Size ayarlanır, ISlideSize::get_Orientation korunur."
type: docs
weight: 53
url: /tr/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) yöntemi

Slayt boyutunu türe göre ayarlar ve mevcut içeriği ölçeklendirir. [SlideSizeType::Custom](../../slidesizetype/) dışındaki herhangi bir değerin atanması, seçilen türe göre [ISlideSize::get_Size](../get_size/) ayarlar, [ISlideSize::get_Orientation](../get_orientation/) korunurken.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Uygulanacak önceden tanımlanmış slayt boyutu. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Kullanılacak içerik ölçeklendirme modu. |

## Açıklamalar

[SlideSizeType::Custom](../../slidesizetype/) dışındaki herhangi bir değerin atanması, seçilen türe göre [System::Drawing::Size](../../../system.drawing/size/) ayarlar, [Orientation](../../orientation/) korunurken.

## ISlideSize::SetSize(float, float, SlideSizeScaleType) yöntemi

Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir. Bu, [ISlideSize::get_Type](../get_type/) değerini [SlideSizeType::Custom](../../slidesizetype/) olarak sıfırlar ve [ISlideSize::get_Orientation](../get_orientation/) ayarlar.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | **float** | Yeni slayt genişliği, nokta cinsinden. |
| height | **float** | Yeni slayt yüksekliği, nokta cinsinden. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Kullanılacak içerik ölçeklendirme modu. |

## Açıklamalar

Bu, [ISlideSize::get_Type](../get_type/) özelliğini [SlideSizeType::Custom](../../slidesizetype/) olarak sıfırlar ve [Orientation](../../orientation/) ayarlar.

## Diğer Bağlantılar

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Sınıf [ISlideSize](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)