---
title: set_Differential()
second_title: Aspose.Slides için C++ API Referansı
description: "Differential True olduğunda, kutu bir diferansiyel gibi davranır (örn., \\uD835\\uDC51\\uD835\\uDC65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false"
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) method

Differential True olduğunda, kutu bir diferansiyel gibi davranır (örneğin, \\uD835\\uDC51\\uD835\\uDC65 bir integrand içinde) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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

* Sınıf [MathBox](../)
* İsim alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)