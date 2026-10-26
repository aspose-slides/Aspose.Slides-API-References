---
title: get_Name()
second_title: Aspose.Slides for C++ API Referansı
description: Fonksiyon adı Örneğin, fonksiyon adları sin ve cos'tur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() method

Fonksiyon adı. Örneğin, fonksiyon adları sin ve cos'tur

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Açıklamalar

Örnek: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathFunction](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)