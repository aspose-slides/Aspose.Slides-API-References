---
title: get_Limit()
second_title: Aspose.Slides for C++ API Referansı
description: Limit argümanı
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() metot

Limit argümanı

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Açıklamalar

Örnek: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)