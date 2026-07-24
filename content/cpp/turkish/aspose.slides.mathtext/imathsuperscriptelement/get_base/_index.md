---
title: get_Base()
second_title: Aspose.Slides için C++ API Referansı
description: Base argümanı
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathsuperscriptelement/get_base/
---
## IMathSuperscriptElement::get_Base() metodu


Base argümanı

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Base()=0
```

## Açıklamalar


Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathSuperscriptElement](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)