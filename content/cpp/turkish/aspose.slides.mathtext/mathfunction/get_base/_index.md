---
title: get_Base()
second_title: Aspose.Slides for C++ API Referansı
description: Fonksiyon Argümanı
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() metod


Fonksiyon Argümanı

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Açıklamalar


Örnek: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathFunction](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)