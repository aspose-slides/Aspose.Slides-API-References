---
title: set_ColumnGap()
second_title: Aspose.Slides için C++ API Referansı
description: "Bir matrisin sütunları arasındaki yatay boşluk değeridir; ColumnGapRule 3 (\"Exactly\") olarak ayarlanmışsa, birim twip (bir noktanın 1/20'si) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") olarak ayarlanmışsa, birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0"
type: docs
weight: 144
url: /tr/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) yöntemi

Bir matrisin sütunları arasındaki yatay boşluk değeridir; ColumnGapRule 3 ("Exactly") olarak ayarlanmışsa, birim twips (bir noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 ("Multiple") olarak ayarlanmışsa, birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda göz ardı edilir. Varsayılan: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## Açıklamalar

Örnek:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Ayrıca Bakınız

* Sınıf [IMathMatrix](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)