---
title: get_Position()
second_title: Aspose.Slides for C++ API Referansı
description: "Gruplama karakterinin konumu. Varsayılan: Bottom"
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() yöntemi

Gruplama karakterinin konumu. Varsayılan: Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Açıklamalar

Örnek: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## İlgili

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Sınıf [IMathGroupingCharacter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)