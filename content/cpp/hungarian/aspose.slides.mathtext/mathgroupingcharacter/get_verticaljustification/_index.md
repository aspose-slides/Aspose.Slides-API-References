---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API-referencia
description: "A csoportkarakter függőleges igazítása. Megadja az objektum elhelyezkedését az alapvonalhoz képest. Például, ha a csoportkarakter az objektum felett van, a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon helyezkedik el; ha a VerticalJustification Bottom értékre van állítva, az objektum alja az alapvonalon van. Alapértelmezett: Bottom, ha Position=Top, és Top, ha Position=Bottom"
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() metódus

Csoportkarakter függőleges igazítása. Meghatározza az objektum igazítását az alapvonalhoz képest. Például, ha a csoportkarakter az objektum felett van, a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon helyezkedik el; ha a VerticalJustification értéke Bottom, az objektum alja az alapvonalon van. Alapértelmezett: Bottom, ha Position=Top, és Top, ha Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
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