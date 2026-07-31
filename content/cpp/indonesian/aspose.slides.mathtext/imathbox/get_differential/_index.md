---
title: get_Differential()
second_title: Referensi API Aspose.Slides untuk C++
description: "Diferensial. Ketika bernilai true, kotak berfungsi sebagai diferensial (misalnya, \\uD835\\uDC51\\uD835\\uDC65 dalam integran), dan menerima spasi horizontal yang sesuai untuk diferensial matematis. Default: false"
type: docs
weight: 66
url: /id/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() metode


Diferensial. Ketika bernilai true, kotak berfungsi sebagai diferensial (misalnya, \\uD835\\uDC51\\uDC65 dalam integran), dan menerima spasi horizontal yang sesuai untuk diferensial matematis. Default: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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

* Kelas [IMathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)