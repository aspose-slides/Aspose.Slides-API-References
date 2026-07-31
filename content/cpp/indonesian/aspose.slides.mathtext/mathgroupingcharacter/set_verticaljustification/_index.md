---
title: set_VerticalJustification()
second_title: Referensi API Aspose.Slides untuk C++
description: "Justifikasi vertikal karakter grup. Menentukan penyelarasan objek relatif terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification of Top menandakan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom"
type: docs
weight: 79
url: /id/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metode


Justifikasi vertikal karakter grup. Menentukan penyelarasan objek relatif terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification of Top menandakan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
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
* Pustaka [Aspose.Slides](../../../)