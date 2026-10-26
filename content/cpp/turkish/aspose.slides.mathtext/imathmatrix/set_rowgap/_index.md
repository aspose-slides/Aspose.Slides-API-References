---
title: set_RowGap()
second_title: Aspose.Slides C++ API Referansı
description: "Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") olarak ayarlanmışsa, birim twip (bir noktanın 1/20'si) olarak yorumlanır. RowGapRule 4 (\"Multiple\") olarak ayarlanmışsa, birim yarım satır olarak yorumlanır. Varsayılan: 0"
type: docs
weight: 196
url: /tr/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) metodu


Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") olarak ayarlanmışsa, birim twip (1/20. nokta) olarak yorumlanır. RowGapRule 4 (\"Multiple\") olarak ayarlanmışsa, birim yarım satır olarak yorumlanır. Varsayılan: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
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
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)