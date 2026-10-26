---
title: set_VerticalJustification()
second_title: Aspose.Slides for C++ API referenciája
description: "A csoportkarakter vertikális igazítása. Meghatározza az objektum elrendezését az alapvonalhoz képest. Például, ha a csoportkarakter az objektum felett helyezkedik el, a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalra esik; ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van. Alapértelmezés: Bottom a Position=Top esetén, és Top a Position=Bottom esetén."
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metódus

A csoportkarakter vertikális igazítása. Megadja az objektum igazítását az alapvonalhoz viszonyítva. Például, ha a csoportkarakter az objektum felett helyezkedik el, a VerticalJustification of Top azt jelenti, hogy az objektum teteje az alapvonalra esik; ha a VerticalJustification Bottom értékre van állítva, akkor az objektum alja az alapvonalon van. Alapértelmezés: Bottom a Position=Top esetén, és Top a Position=Bottom esetén.

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Megjegyzések

Példa: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Lásd még

* Enumeráció [MathTopBotPositions](../../mathtopbotpositions/)
* Osztály [IMathGroupingCharacter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)