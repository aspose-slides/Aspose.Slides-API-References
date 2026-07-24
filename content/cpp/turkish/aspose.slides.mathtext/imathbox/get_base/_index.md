---
title: get_Base()
second_title: Aspose.Slides C++ API Referansı
description: Base argüman
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() yöntemi

Base argüman

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## Açıklamalar

Örnek: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## Diğer Bilgiler

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathBox](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)