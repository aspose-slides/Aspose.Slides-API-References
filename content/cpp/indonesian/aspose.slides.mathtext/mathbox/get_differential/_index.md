---
title: get_Differential()
second_title: Referensi API Aspose.Slides untuk C++
description: "Differential Jika true, kotak berperilaku sebagai differential (misalnya, \\uD835\\uDC51\\uD835\\uDC65 dalam integran), dan menerima spasi horizontal yang sesuai untuk differential matematis. Default: false"
type: docs
weight: 66
url: /id/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() metode

Differential Jika true, kotak berperilaku sebagai differential (e.g., \\uD835\\uDC51\\uDC65 dalam integran), dan menerima spasi horizontal yang sesuai untuk differential matematis. Default: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
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

* Kelas [MathBox](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)