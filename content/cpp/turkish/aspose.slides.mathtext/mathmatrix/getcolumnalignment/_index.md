---
title: GetColumnAlignment()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sütunun yatay hizalamasını al
type: docs
weight: 248
url: /tr/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) metodu

Belirtilen sütunun yatay hizalamasını al

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| columnIndex | **int32_t** | Sıfır tabanlı sütun indeksi |

### Dönüş Değeri

Belirtilen sütunun yatay hizalaması

## Açıklamalar

Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Bakınız

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Sınıf [MathMatrix](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)