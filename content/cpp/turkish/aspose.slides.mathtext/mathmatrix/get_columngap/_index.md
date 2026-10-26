---
title: get_ColumnGap()
second_title: Aspose.Slides için C++ API Referansı
description: "Matrisin sütunları arasındaki yatay boşluğun değeri; ColumnGapRule 3 (\"Exactly\") olarak ayarlanmışsa, birim twip (bir noktanın 1/20'si) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") olarak ayarlanmışsa, birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0"
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() metodu

Matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 ("Exactly") olarak ayarlanmışsa, birim twip (bir noktanın 1/20'si) olarak yorumlanır. ColumnGapRule 4 ("Multiple") olarak ayarlanmışsa, birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda görmezden gelinir. Varsayılan: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Açıklamalar

Örnek:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Bakınız

* Sınıf [MathMatrix](../)
* İsim alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)