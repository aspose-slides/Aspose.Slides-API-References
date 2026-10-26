---
title: set_RowGapRule()
second_title: Aspose.Slides için C++ API Referansı
description: "Matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya puan (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0)"
type: docs
weight: 170
url: /tr/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) metot


Bir matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya puan (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Ayrıca Bakınız

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)