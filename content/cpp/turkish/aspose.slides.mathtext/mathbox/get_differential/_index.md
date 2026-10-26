---
title: get_Differential()
second_title: Aspose.Slides C++ API Referansı
description: "Differential true olduğunda, kutu bir diferansiyel olarak davranır (örnek, \\uD835\\uDC51\\uD835\\uDC65 bir integrand içinde), ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false"
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() yöntemi


Differential true olduğunda, kutu bir diferansiyel olarak davranır (örnek, \\uD835\\uDC51\\uD835\\uDC65 bir integrand içinde), ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## Açıklamalar


Örnek: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Bakınız

* Sınıf [MathBox](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)