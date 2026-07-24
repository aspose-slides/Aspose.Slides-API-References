---
title: get_Base()
second_title: Aspose.Slides için C++ API Referansı
description: Base argümanı
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() metodu


Base argümanı

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Açıklamalar


Örnek: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathRadical](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)