---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API Referansı
description: "Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, VerticalJustification of Top, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir; VerticalJustification Bottom ayarlandığında, nesnenin alt kısmı temel çizgide olur. Default: Bottom for Position=Top, and Top for Position=Bottom"
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() method


Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, Top değerindeki VerticalJustification, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir; VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide olur. Varsayılan: Bottom for Position=Top, and Top for Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## Açıklamalar


Örnek: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Diğer Bağlantılar

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Sınıf [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)