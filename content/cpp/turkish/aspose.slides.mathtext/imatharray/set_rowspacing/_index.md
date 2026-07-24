---
title: set_RowSpacing()
second_title: Aspose.Slides için C++ API Referansı
description: "Bir dizinin satırları arasındaki boşluk. Sadece RowSpacingRule 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi points, Multiple durumunda ise ölçü birimi half-lines olur. Varsayılan: 0"
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) method


Bir dizinin satırları arasındaki boşluk Sadece RowSpacingRule 3 olarak ayarlandığında kullanılır Tam olarak bu durumda ölçü birimi points veya Multiple durumunda ölçü birimi half-lines olur. Varsayılan: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Diğer

* Sınıf [IMathArray](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)