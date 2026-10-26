---
title: GetTile()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen renklerle desen doldurması için bir döşeme resmi oluşturur.
type: docs
weight: 53
url: /tr/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metodu

Belirtilen renklerle desen doldurması için bir döşeme resmi oluşturur.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Desen için arka plan [System::Drawing::Color](../../../system.drawing/color/) |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Desen için ön plan [System::Drawing::Color](../../../system.drawing/color/) |

### Dönüş Değeri

Döşeme [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) metodu

Desen doldurması için bir döşeme resmi oluşturur.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Varsayılan [System::Drawing::Color](../../../system.drawing/color/) |

### Dönüş Değeri

Döşeme [IImage](../../iimage/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IImage](../../iimage/)
* Sınıf [Color](../../../system.drawing/color/)
* Sınıf [PatternFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)