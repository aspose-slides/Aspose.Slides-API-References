---
title: set_LimitLocation()
second_title: Aspose.Slides for C++ API Referansı
description: Limitlerin konumu (alt simge ve üst simge)
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) metot

Limitlerin konumu (alt simge ve üst simge)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Açıklamalar

Örnek:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Ayrıca Bakın

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Sınıf [MathNaryOperator](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)