---
title: get_VerticalJustification()
second_title: Referensi API Aspose.Slides untuk C++
description: "Justifikasi vertikal karakter grup. Menentukan perataan objek terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification of Top menandakan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom"
type: docs
weight: 66
url: /id/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() metode

Justifikasi vertikal karakter grup. Menentukan perataan objek relatif terhadap garis dasar. Sebagai contoh, ketika karakter grup berada di atas objek, VerticalJustification of Top menandakan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## Catatan

Contoh:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Lihat Juga

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Kelas [MathGroupingCharacter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)