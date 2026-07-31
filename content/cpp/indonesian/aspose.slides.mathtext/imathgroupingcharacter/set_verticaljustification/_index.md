---
title: set_VerticalJustification()
second_title: Referensi API Aspose.Slides untuk C++
description: "Justifikasi vertikal karakter grup. Menentukan penyelarasan objek terhadap garis dasar. Sebagai contoh, ketika karakter grup berada di atas objek, VerticalJustification dengan nilai Top menunjukkan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom"
type: docs
weight: 79
url: /id/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metode

Justifikasi vertikal karakter grup. Menentukan penyelarasan objek terhadap garis dasar. Sebagai contoh, ketika karakter grup berada di atas objek, VerticalJustification dengan nilai Top menunjukkan bahwa bagian atas objek berada pada garis dasar; ketika VerticalJustification diatur ke Bottom, bagian bawah objek berada pada garis dasar Default: Bottom untuk Position=Top, dan Top untuk Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
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
* RuangNama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)