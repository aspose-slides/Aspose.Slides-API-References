---
title: set_VerticalJustification()
second_title: Aspose.Slides için C++ API Referansı
description: "Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üstünde olduğunda, Top değerindeki VerticalJustification, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir; VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide olur. Varsayılan: Position=Top için Bottom ve Position=Bottom için Top"
type: docs
weight: 79
url: /tr/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metod

Grup karakterinin dikey hizalaması. Nesnenin temel çizgiye göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üstünde olduğunda, Top değerindeki VerticalJustification, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir; VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide olur. Varsayılan: Position=Top için Bottom ve Position=Bottom için Top.

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Açıklamalar

Örnek:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## İlgili

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Sınıf [MathGroupingCharacter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)