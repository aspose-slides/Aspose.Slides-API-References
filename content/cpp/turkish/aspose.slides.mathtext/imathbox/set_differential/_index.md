---
title: set_Differential()
second_title: Aspose.Slides for C++ API Referansı
description: "Diferansiyel. true olduğunda, kutu bir diferansiyel gibi davranır (ör. \\uD835\\uDC51\\uD835\\uDC65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false"
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) metodu


Diferansiyel. true olduğunda, kutu bir diferansiyel gibi davranır (ör. \\uD835\\uDC51\\uD835\\uDC65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Diğer Bağlantılar

* Sınıf [IMathBox](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)