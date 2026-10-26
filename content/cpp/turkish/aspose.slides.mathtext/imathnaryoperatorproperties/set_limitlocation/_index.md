---
title: set_LimitLocation()
second_title: Aspose.Slides for C++ API Referansı
description: Sınırlamaların konumu (alt ve üst gösterim)
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) metodu


Sınırlamaların konumu (alt ve üst gösterim)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Ayrıca Bakınız

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Sınıf [IMathNaryOperatorProperties](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)