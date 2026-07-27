---
title: set_Position()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Posición del carácter de agrupación. Predeterminado: Bottom"
type: docs
weight: 53
url: /es/aspose.slides.mathtext/imathgroupingcharacter/set_position/
---
## IMathGroupingCharacter::set_Position(MathTopBotPositions) método

Posición del carácter de agrupación. Predeterminado: Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Position(MathTopBotPositions value)=0
```

## Observaciones

Ejemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Ver también

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)