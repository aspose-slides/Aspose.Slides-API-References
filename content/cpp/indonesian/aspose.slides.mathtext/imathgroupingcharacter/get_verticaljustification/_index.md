---
title: get_VerticalJustification()
second_title: Referensi API Aspose.Slides untuk C++
description: "Penempatan vertikal karakter grup. Menentukan perataan objek terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification dengan Top menunjukkan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom"
type: docs
weight: 66
url: /id/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() metode

Penempatan vertikal karakter grup. Menentukan perataan objek relatif terhadap garis dasar. Misalnya, ketika karakter grup berada di atas objek, VerticalJustification dengan Top menunjukkan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Catatan

Contoh: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Lihat Juga

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Kelas [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)