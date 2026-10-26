---
title: set_ColumnGap()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 (\"Exactly\") olarak ayarlanmışsa birim twip (bir noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") olarak ayarlanmışsa birim 0.5 em artışlarının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0"
type: docs
weight: 144
url: /tr/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) metodu


Bir matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 ("Exactly") olarak ayarlanmışsa birim twip (bir noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 ("Multiple") olarak ayarlanmışsa birim 0.5 em artışlarının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
```

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Ayrıca Bakınız

* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)