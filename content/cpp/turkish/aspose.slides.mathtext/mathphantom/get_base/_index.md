---
title: get_Base()
second_title: Aspose.Slides for C++ API Referansı
description: Base argümanı
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() yöntemi


Base argümanı

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathPhantom](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)