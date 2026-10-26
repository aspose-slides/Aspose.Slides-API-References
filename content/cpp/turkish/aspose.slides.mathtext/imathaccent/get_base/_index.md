---
title: get_Base()
second_title: Aspose.Slides for C++ API Referansı
description: Aksentin uygulandığı argüman
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() metod


Aksentin uygulandığı argüman

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## Açıklamalar


Örnek: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Ayrıca bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathAccent](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)