---
title: GetTile()
second_title: C++ için Aspose.Slides API Referansı
description: Belirtilen renklerle desen dolgusuna ait bir döşeme resmi oluşturur.
type: docs
weight: 53
url: /tr/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method

Belirtilen renklerle desen dolgusuna ait bir döşeme resmi oluşturur.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Desen için [System::Drawing::Color](../../../system.drawing/color/) arka plan. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Desen için [System::Drawing::Color](../../../system.drawing/color/) ön plan. |

### Dönüş Değeri

Döşeme [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) method

Desen dolgusuna ait bir döşeme resmi oluşturur.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | ShapeEx'in StyleEx nesnesinde tanımlanan varsayılan [System::Drawing::Color](../../../system.drawing/color/). Doldurmanın renkleri buna bağlı olabilir. |

### Dönüş Değeri

Döşeme [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IImage](../../iimage/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [IPatternFormat](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)