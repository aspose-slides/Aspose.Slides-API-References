---
title: get_Differential()
second_title: Aspose.Slides for C++ API Referansı
description: "Differential. true olduğunda, kutu bir diferansiyel gibi davranır (ör. \\uD835\\uDC51\\uD835\\uDC65 bir integrand içinde), ve matematiksel diferansiyel için uygun yatay boşluğu alır. Default: false"
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() metodu


Differential. true olduğunda, kutu bir diferansiyel gibi davranır (ör. \\uD835\\uDC51\\uD835\\uDC65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Default: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
```

## Açıklamalar


Örnek: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Ayrıca Bakınız

* Sınıf [IMathBox](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)