---
title: get_LimitLocation()
second_title: Aspose.Slides için C++ API Referansı
description: Sınırlamaların konumu (alt simge ve üst simge)
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() metodu


Sınırlamaların konumu (alt simge ve üst simge)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Açıklamalar


Örnek: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## İlgili


* Enum [MathLimitLocations](../../mathlimitlocations/)
* Sınıf [IMathNaryOperatorProperties](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)