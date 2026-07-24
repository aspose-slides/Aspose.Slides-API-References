---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri ems veya puan (twips olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0)"
type: docs
weight: 105
url: /tr/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() metodu


Bir matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri ems veya puan (twips olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## İlgili

* Enum [MathSpacingRules](../../mathspacingrules/)
* Sınıf [MathMatrix](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)