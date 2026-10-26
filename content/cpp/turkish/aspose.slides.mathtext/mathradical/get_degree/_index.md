---
title: get_Degree()
second_title: Aspose.Slides için C++ API Referansı
description: Derece argümanı
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() metod


Derece argümanı

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Açıklamalar


Örnek: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathRadical](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)