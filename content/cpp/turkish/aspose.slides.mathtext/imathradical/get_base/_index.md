---
title: get_Base()
second_title: Aspose.Slides for C++ API Referansı
description: Taban argümanı
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() metodu


Taban argümanı

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Açıklamalar


Örnek: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // küp kökü
auto baseElem = radical->get_Base();
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathRadical](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)