---
title: get_RowGap()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") olarak ayarlandığında, birim twip (noktanın 1/20'si) olarak yorumlanır RowGapRule 4 (\"Multiple\") olarak ayarlandığında, birim yarım satır olarak yorumlanır. Varsayılan: 0"
type: docs
weight: 183
url: /tr/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() metot


Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") olarak ayarlanmışsa, birim twip olarak yorumlanır (noktanın 1/20'si) RowGapRule 4 (\"Multiple\") olarak ayarlanmışsa, birim yarım satır olarak yorumlanır. Varsayılan: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Diğer

* Sınıf [MathMatrix](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)