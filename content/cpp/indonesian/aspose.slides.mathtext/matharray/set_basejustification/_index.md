---
title: set_BaseJustification()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan penyelarasan array relatif terhadap teks di sekitarnya. Teks di luar array dapat diselaraskan dengan bagian bawah, atas, atau tengah dari objek array. Nilai default: Center"
type: docs
weight: 27
url: /id/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) metode

Menentukan penyelarasan array relatif terhadap teks di sekitarnya. Teks di luar array dapat diselaraskan dengan bottom, top, atau center dari objek array. Nilai default: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
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