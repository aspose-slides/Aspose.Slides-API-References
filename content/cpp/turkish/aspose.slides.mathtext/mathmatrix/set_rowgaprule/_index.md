---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API Referansı
description: "Matris satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya nokta (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0)"
type: docs
weight: 170
url: /tr/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) metodu


Matris satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya puan (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Ayrıca Bakınız

* Enum [MathSpacingRules](../../mathspacingrules/)
* Sınıf [MathMatrix](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)