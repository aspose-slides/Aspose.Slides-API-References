---
title: set_BaseJustification()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, bagian atas, atau tengah objek array. Nilai default: Center"
type: docs
weight: 27
url: /id/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) metode


Menentukan perataan array relatif terhadap teks di sekitarnya. Teks di luar array dapat disejajarkan dengan bagian bawah, bagian atas, atau tengah objek array. Nilai default: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Catatan


Contoh: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Lihat Juga

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Kelas [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)