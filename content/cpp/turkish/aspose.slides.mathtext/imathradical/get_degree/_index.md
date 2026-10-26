---
title: get_Degree()
second_title: Aspose.Slides için C++ API Referansı
description: Derece argümanı
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() yöntemi


Derece argümanı

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Açıklamalar


Örnek: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // küp kökü
auto degreeElem = radical->get_Degree();
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathRadical](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)