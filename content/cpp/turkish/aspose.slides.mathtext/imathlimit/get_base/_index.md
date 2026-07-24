---
title: get_Base()
second_title: Aspose.Slides for C++ API Referansı
description: Base argüman
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() metodu

Base argüman

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## Açıklamalar


Örnek: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## İlgili

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathLimit](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)