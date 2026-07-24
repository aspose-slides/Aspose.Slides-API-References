---
title: get_Base()
second_title: Aspose.Slides için C++ API Referansı
description: Fonksiyon Argümanı
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() metodu


Fonksiyon Argümanı

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
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
* Sınıf [IMathFunction](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)