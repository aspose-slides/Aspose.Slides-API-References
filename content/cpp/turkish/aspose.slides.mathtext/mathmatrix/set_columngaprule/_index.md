---
title: set_ColumnGapRule()
second_title: Aspose.Slides için C++ API Referansı
description: "Bir matrisin sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya point (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0)"
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) method


Bir matrisin sütunları arasındaki yatay boşluk tipi; Yatay boşluk birimleri ems veya point (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## Açıklamalar


Örnek:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Diğer Bağlantılar

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)