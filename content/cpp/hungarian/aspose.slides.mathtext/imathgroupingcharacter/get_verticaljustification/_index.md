---
title: get_VerticalJustification()
second_title: Aspose.Slides C++ API referencia
description: "A csoport karakter vertikális igazítása. Meghatározza az objektum igazítását az alapvonalhoz képest. Például, ha a csoport karakter az objektum felett helyezkedik el, a Top értékű VerticalJustification azt jelenti, hogy az objektum felső része az alapvonalon van; ha a VerticalJustification értéke Bottom, akkor az objektum alsó része az alapvonalon található. Alapértelmezett: Bottom a Position=Top esetén, és Top a Position=Bottom esetén."
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() metódus


Vertikális igazítás a csoport karakterhez. Meghatározza az objektum igazítását az alapvonalhoz képest. Például, ha a csoport karakter az objektum fölött van, a Top értékű VerticalJustification azt jelenti, hogy az objektum felső része az alapvonalon helyezkedik el; ha a VerticalJustification értéke Bottom, az objektum alsó része van az alapvonalon. Alapértelmezett: Bottom a Position=Top esetén, és Top a Position=Bottom esetén.

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Megjegyzések


Példa: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Lásd még

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Osztály [IMathGroupingCharacter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)