---
title: get_Base()
second_title: Aspose.Slides C++ API Referansı
description: Base argümanı
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() metodu


Base argümanı

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## Açıklamalar


Örnek: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathBorderBox](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)