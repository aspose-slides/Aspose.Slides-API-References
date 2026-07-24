---
title: get_Base()
second_title: Aspose.Slides için C++ API Referansı
description: Aksentin uygulandığı argüman
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() metot


Aksentin uygulandığı argüman

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Açıklamalar


Örnek: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathAccent](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)