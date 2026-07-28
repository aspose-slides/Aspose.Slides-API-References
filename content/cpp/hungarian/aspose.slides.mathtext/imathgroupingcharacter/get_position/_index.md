---
title: get_Position()
second_title: Aspose.Slides for C++ API referencia
description: "A csoportosító karakter pozíciója. Alapértelmezett: Alul"
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() metódus

A csoportosító karakter pozíciója. Alapértelmezett: Alul

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Megjegyzések

Példa: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Lásd még

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Osztály [IMathGroupingCharacter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)