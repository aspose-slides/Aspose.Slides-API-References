---
title: get_RowGap()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") olarak ayarlanırsa, birim twip (bir noktanın 1/20'si) olarak yorumlanır. RowGapRule 4 (\"Multiple\") olarak ayarlanırsa, birim yarım satır olarak yorumlanır. Varsayılan: 0"
type: docs
weight: 183
url: /tr/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() metot

Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 ("Exactly") olarak ayarlanırsa, birim twip (bir noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 ("Multiple") olarak ayarlanırsa, birim yarım satır olarak yorumlanır. Varsayılan: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Açıklamalar

Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Ayrıca Bakınız

* Sınıf [IMathMatrix](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)