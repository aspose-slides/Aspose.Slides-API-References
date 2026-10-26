---
title: set_RowGap()
second_title: Aspose.Slides C++ API Referansı
description: "Matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. RowGapRule 4 (\"Multiple\") olarak ayarlanmışsa birim yarı satır olarak yorumlanır. Varsayılan: 0"
type: docs
weight: 196
url: /tr/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) yöntemi

Matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 ("Multiple") olarak ayarlanmışsa birim yarı satır olarak yorumlanır. Varsayılan: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## Açıklamalar

Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Diğer Bağlantılar

* Sınıf [MathMatrix](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)