---
title: get_Base()
second_title: Aspose.Slides için C++ API Referansı
description: Base argüman
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() metot


Base argüman

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## Açıklamalar


Örnek: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## Bkz

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathNaryOperator](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)