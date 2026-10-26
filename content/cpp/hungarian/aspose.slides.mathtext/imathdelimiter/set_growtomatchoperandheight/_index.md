---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API referencia
description: Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha true, a határolók függőlegesen nőnek, hogy megfeleljenek az operandus magasságának. Az alapértelmezett érték true.
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) metódus

Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha true, a határolók függőlegesen nőnek, hogy megfeleljenek az operandus magasságának. Az alapértelmezett érték true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## Megjegyzések

Példa:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Lásd még

* Osztály [IMathDelimiter](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)