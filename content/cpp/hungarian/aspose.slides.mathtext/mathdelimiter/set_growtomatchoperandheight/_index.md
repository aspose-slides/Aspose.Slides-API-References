---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API hivatkozás
description: Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha true, a határolók függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. Az alapértelmezett érték true
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) metódus

Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha true, a határoló függőlegesen nő, hogy illeszkedjen az operandus magasságához. Az alapértelmezett érték true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## Megjegyzések

Példa: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Lásd még

* Osztály [MathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)