---
title: get_RowSpacing()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir dizinin satırları arasındaki boşluk yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi points veya Multiple olduğunda ölçü birimi yarı satırdır. Varsayılan: 0"
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() metodu

Bir dizinin satırları arasındaki boşluk yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi points veya Multiple olduğunda ölçü birimi yarı-satırdır. Varsayılan: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Açıklamalar

Örnek: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Bakınız

* Sınıf [IMathArray](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)