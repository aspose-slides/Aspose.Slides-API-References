---
title: GetTile()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen renklerle desen dolgu için bir döşeme resmi oluşturur.
type: docs
weight: 53
url: /tr/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) yöntemi


Belirtilen renklerle desen dolgu için bir döşeme resmi oluşturur.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Desen için [System::Drawing::Color](../../../system.drawing/color/) arka planı. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Desen için [System::Drawing::Color](../../../system.drawing/color/) ön planı. |

### Dönüş Değeri

Döşeme [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) yöntemi


Desen dolgu için bir döşeme resmi oluşturur.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | ShapeEx'in StyleEx nesnesinde tanımlanan varsayılan [System::Drawing::Color](../../../system.drawing/color/). Doldurmanın renkleri buna bağlı olabilir. |

### Dönüş Değeri

Döşeme [IImage](../../iimage/).

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IImage](../../iimage/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [IPatternFormat](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)