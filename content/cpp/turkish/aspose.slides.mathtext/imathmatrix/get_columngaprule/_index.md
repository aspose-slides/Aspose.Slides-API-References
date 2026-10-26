---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir matristeki sütunlar arasındaki yatay boşluk türü; Yatay boşluk birimleri ems veya puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)"
type: docs
weight: 105
url: /tr/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() metod

Bir matristeki sütunlar arasındaki yatay boşluk türü; Yatay boşluk birimleri ems veya puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Açıklamalar

Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Ayrıca Bakınız

* Enum [MathSpacingRules](../../mathspacingrules/)
* Sınıf [IMathMatrix](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)