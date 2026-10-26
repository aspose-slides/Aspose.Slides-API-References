---
title: get_RowGapRule()
second_title: Aspose.Slides için C++ API Referansı
description: "Bir matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya nokta (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)"
type: docs
weight: 157
url: /tr/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() metot


Bir matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya nokta (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Diğerlerine Bakın

* Enum [MathSpacingRules](../../mathspacingrules/)
* Sınıf [MathMatrix](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)