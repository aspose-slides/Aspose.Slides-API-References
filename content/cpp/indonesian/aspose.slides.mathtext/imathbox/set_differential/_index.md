---
title: set_Differential()
second_title: Referensi API Aspose.Slides untuk C++
description: "Diferensial. Ketika true, kotak berperilaku sebagai diferensial (mis., \\uD835\\uDC51\\uD835\\uDC65 dalam sebuah integran), dan menerima spasi horizontal yang tepat untuk diferensial matematis. Default: false"
type: docs
weight: 79
url: /id/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) metode


Diferensial. Jika true, kotak berperilaku sebagai diferensial (misalnya, \\uD835\\uDC51\\uD835\\uDC65 dalam sebuah integran), dan menerima spasi horizontal yang tepat untuk diferensial matematis. Default: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## Catatan


Contoh: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Lihat Juga

* Kelas [IMathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)