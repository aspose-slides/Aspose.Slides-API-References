---
title: get_Limit()
second_title: Aspose.Slides for C++ API Referansı
description: Limit argümanı
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() yöntemi


Limit argümanı

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Açıklamalar


Örnek: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Diğer

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathLimit](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)