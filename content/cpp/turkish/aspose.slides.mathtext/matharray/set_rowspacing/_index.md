---
title: set_RowSpacing()
second_title: Aspose.Slides için C++ API Referansı
description: "Bir dizinin satırları arasındaki boşluk. RowSpacingRule yalnızca 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi puan, Multiple olduğunda ölçü birimi yarı satırdır. Varsayılan: 0"
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) method

Dizinin satırları arasındaki boşluk. RowSpacingRule yalnızca 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi puan, Multiple olduğunda ölçü birimi yarı satırdır. Varsayılan: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## Açıklamalar

Örnek: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Ayrıca Bakınız

* Sınıf [MathArray](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)