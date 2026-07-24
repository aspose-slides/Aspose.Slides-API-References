---
title: get_RowSpacing()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir dizinin satırları arasındaki boşluk RowSpacingRule 3 olarak ayarlandığında yalnızca kullanılır. Bu durumda ölçü birimi points, Multiple olduğunda ise ölçü birimi half-lines. Varsayılan: 0"
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() metodu


Bir dizinin satırları arasındaki boşluk. Bu, yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi points olur; Multiple durumda ölçü birimi half-lines olur. Varsayılan: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Notlar


Örnek: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Ayrıca

* Sınıf [MathArray](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)