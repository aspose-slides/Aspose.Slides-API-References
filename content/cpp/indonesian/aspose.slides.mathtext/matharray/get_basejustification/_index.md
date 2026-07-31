---
title: get_BaseJustification()
second_title: Aspose.Slides untuk C++ API Reference
description: "Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah dari objek array. Nilai default: Center"
type: docs
weight: 14
url: /id/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() metode

Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, atas, atau tengah dari objek array. Nilai default: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Catatan

Contoh:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Lihat Juga

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Kelas [MathArray](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)