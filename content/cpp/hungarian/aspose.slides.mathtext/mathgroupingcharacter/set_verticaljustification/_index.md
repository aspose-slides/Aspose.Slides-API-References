---
title: set_VerticalJustification()
second_title: Aspose.Slides C++ API hivatkozás
description: "A csoportkarakter függőleges igazítása. Megadja az objektum igazítását az alapvonalhoz képest. Például, ha a csoportkarakter az objektum felett van, a Top értékű függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon van; ha a függőleges igazítás Bottom-ra van állítva, az objektum alja az alapvonalon van. Alapértelmezés: Bottom a Position=Top esetén, és Top a Position=Bottom esetén."
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metódus

A csoportkarakter függőleges igazítása. Meghatározza az objektum igazítását az alapvonalhoz viszonyítva. Például, ha a csoportkarakter az objektum felett helyezkedik el, a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon van; ha a függőleges igazítás Bottom-ra van állítva, az objektum alja az alapvonalon van. Alapértelmezés: Bottom, ha Position=Top, és Top, ha Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Megjegyzések

Példa:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Lásd még

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Osztály [MathGroupingCharacter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)