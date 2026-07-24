---
title: get_RowGapRule()
second_title: Aspose.Slides for C++ API Referansı
description: "Matrisin satırları arasındaki dikey boşluğun türü; Dikey boşluk birimleri satır ya da nokta (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)"
type: docs
weight: 157
url: /tr/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() metodu


Matrisin satırları arasındaki dikey boşluğun türü; Dikey boşluk birimleri satır veya nokta (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Ayrıca Bakınız

* Enum [MathSpacingRules](../../mathspacingrules/)
* Sınıf [IMathMatrix](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)