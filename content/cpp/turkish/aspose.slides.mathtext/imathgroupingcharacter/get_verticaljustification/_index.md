---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API Referansı
description: "Grup karakterinin düşey hizalaması. Nesnenin temel çizgiye göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, Top olarak ayarlanan VerticalJustification, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir; VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide olur. Varsayılan: Position=Top için Bottom, ve Position=Bottom için Top"
type: docs
weight: 66
url: /tr/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() metodu

Grup karakterinin düşey hizalaması. Nesnenin temel çizgiye göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, VerticalJustification değeri Top, nesnenin üst kısmının temel çizgiye denk geldiğini gösterir; VerticalJustification Bottom olarak ayarlandığında, nesnenin alt kısmı temel çizgide yer alır. Varsayılan: Position=Top için Bottom, ve Position=Bottom için Top

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Açıklamalar

Örnek: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Bakınız

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Sınıf [IMathGroupingCharacter](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)