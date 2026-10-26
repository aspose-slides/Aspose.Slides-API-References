---
title: get_BaseJustification()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan justifikasi vertikal terhadap teks di sekitarnya. Nilai yang mungkin adalah top, bottom, dan center. Default: Center"
type: docs
weight: 53
url: /id/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() metode


Menentukan justifikasi vertikal relatif terhadap teks di sekitarnya. Nilai yang mungkin adalah top, bottom, dan center. Default: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Catatan


Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Lihat Juga

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Kelas [IMathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)