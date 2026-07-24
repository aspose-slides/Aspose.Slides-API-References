---
title: get_Arguments()
second_title: Aspose.Slides için C++ API Referansı
description: Ayırıcı karakterlerle ayrılmış bir veya daha fazla matematiksel öğe
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() metodu


Ayırıcı karakterlerle ayrılmış bir veya daha fazla matematiksel öğe

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElementCollection](../../imathelementcollection/)
* Sınıf [MathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)