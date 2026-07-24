---
title: SetSize()
second_title: Aspose.Slides for C++ API Referansı
description: Tipine göre slayt boyutunu ayarlar ve mevcut içeriği ölçeklendirir.
type: docs
weight: 53
url: /tr/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) yöntemi

Slayt boyutunu türe göre ayarlar ve mevcut içeriği ölçeklendirir.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Uygulanacak önceden tanımlı slayt boyutu. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Kullanılacak içerik ölçekleme modu. |
## Açıklamalar

[SlideSizeType::Custom](../../slidesizetype/) dışındaki herhangi bir değer atandığında, seçilen türe göre [SlideSize::get_Size](../get_size/) ayarlanır ve [SlideSize::get_Orientation](../get_orientation/) korunur. 

## SlideSize::SetSize(float, float, SlideSizeScaleType) yöntemi

Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | **float** | Yeni slayt genişliği, nokta cinsinden. |
| height | **float** | Yeni slayt yüksekliği, nokta cinsinden. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Kullanılacak içerik ölçekleme modu. |
## Açıklamalar

Bu, [SlideSize::get_Type](../get_type/) özelliğini [SlideSizeType::Custom](../../slidesizetype/) olarak sıfırlar ve [Orientation](../../orientation/) ayarlar. 

## İlgili

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Sınıf [SlideSize](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)