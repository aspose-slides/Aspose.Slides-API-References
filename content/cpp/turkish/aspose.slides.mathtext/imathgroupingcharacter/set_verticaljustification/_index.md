---
title: set_VerticalJustification()
second_title: Aspose.Slides for C++ API Referansı
description: "Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, Top olarak ayarlanan VerticalJustification, nesnenin üst kısmının temel çizgide olduğunu gösterir; VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide olur. Varsayılan: Position=Top için Bottom, Position=Bottom için Top"
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) yöntemi

Grup karakterinin dikey hizalaması. Nesnenin taban çizgisine göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, Top dikey hizalaması nesnenin üst kısmının taban çizgisine denk geldiğini; Bottom olarak ayarlandığında ise nesnenin alt kısmının taban çizgisinde olduğunu gösterir. Varsayılan: Position=Top için Bottom, Position=Bottom için Top

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Açıklamalar

Örnek: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## İlgili

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)