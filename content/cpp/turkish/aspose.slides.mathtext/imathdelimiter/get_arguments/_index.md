---
title: get_Arguments()
second_title: Aspose.Slides için C++ API Referansı
description: Ayırıcı karakterlerle ayrılmış bir veya daha fazla matematiksel öğe
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() metodu


Ayırıcı karakterlerle ayrılmış bir veya daha fazla matematiksel öğe

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Açıklamalar


Örnek:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElementCollection](../../imathelementcollection/)
* Sınıf [IMathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)