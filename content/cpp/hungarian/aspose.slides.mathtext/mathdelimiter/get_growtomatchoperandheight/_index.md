---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API hivatkozás
description: Meghatározza a BeginningCharacter, a SeparatorCharacter és az EndingCharacter növekedését. Ha true, a határolók függőlegesen nőnek, hogy megfeleljenek az operandus magasságának. Az alapértelmezett érték true
type: docs
weight: 92
url: /hu/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() metódus

Meghatározza a BeginningCharacter, a SeparatorCharacter és az EndingCharacter növekedését. Ha true, a határolók függőlegesen nőnek, hogy megfeleljenek az operandus magasságának. Az alapértelmezett érték true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Megjegyzés

Példa: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Lásd még

* Osztály [MathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)