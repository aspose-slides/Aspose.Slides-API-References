---
title: get_Position()
second_title: Referensi API Aspose.Slides untuk C++
description: "Posisi karakter pengelompokan. Default: Bottom"
type: docs
weight: 40
url: /id/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() metode

Posisi karakter pengelompokan. Default: Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Catatan

Contoh: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Lihat Juga

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Kelas [IMathGroupingCharacter](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)