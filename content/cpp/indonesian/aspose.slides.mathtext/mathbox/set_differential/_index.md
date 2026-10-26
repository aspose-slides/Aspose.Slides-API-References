---
title: set_Differential()
second_title: Referensi API Aspose.Slides untuk C++
description: "Differential When true, the box acts as a differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 dalam suatu integrand), dan menerima spasi horizontal yang sesuai untuk diferensial matematis. Default: false"
type: docs
weight: 79
url: /id/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) metode


Differential Jika true, kotak bertindak sebagai diferensial (mis., \\uD835\\uDC51\\uDC65 dalam suatu integran), dan menerima spasi horizontal yang sesuai untuk diferensial matematis. Default: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## Keterangan


Contoh: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Lihat Juga

* Kelas [MathBox](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)