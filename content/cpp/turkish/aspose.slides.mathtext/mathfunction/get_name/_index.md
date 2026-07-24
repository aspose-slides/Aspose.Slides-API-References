---
title: get_Name()
second_title: Aspose.Slides için C++ API Referansı
description: Fonksiyon adı Örneğin, fonksiyon adları sin ve cos'tur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() yöntemi


Fonksiyon adı Örneğin, fonksiyon adları sin ve cos'tur

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Açıklamalar


Örnek: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathFunction](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)