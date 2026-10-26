---
title: get_LimitLocation()
second_title: Aspose.Slides for C++ API Referansı
description: Sınırların konumu (alt simge ve üst simge)
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() metodu


Sınırların konumu (alt simge ve üst simge)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Açıklamalar


Örnek: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Bakınız

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Sınıf [MathNaryOperator](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)