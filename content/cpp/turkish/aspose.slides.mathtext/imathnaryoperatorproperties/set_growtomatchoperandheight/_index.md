---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides için C++ API Referansı
description: Operatör karakteri, operant yüksekliğine uyacak şekilde dikey olarak büyür
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) metod


Operatör karakteri, operant yüksekliğine uyması için dikey olarak büyür

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Ayrıca Bakınız

* Sınıf [IMathNaryOperatorProperties](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)