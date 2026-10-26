---
title: get_ColumnGap()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir matrisin sütunları arasındaki yatay boşluğun değeri; ColumnGapRule 3 (\"Exactly\") olarak ayarlandığında birim twip (bir puanın 1/20'si) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") olarak ayarlandığında birim 0.5 em artışlarının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0"
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() metod


Bir matrisin sütunları arasındaki yatay boşluk değeri; Eğer ColumnGapRule 3 (\"Exactly\") olarak ayarlanırsa, birim twips (bir puanın 1/20'i) olarak yorumlanır. Eğer ColumnGapRule 4 (\"Multiple\") olarak ayarlanırsa, birim 0.5 em artışlarının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## İlgili

* Sınıf [IMathMatrix](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)