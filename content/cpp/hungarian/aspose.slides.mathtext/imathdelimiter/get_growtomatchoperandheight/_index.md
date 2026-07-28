---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha true, a határolók függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. Az alapértelmezett érték true
type: docs
weight: 92
url: /hu/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() metódus

Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha true, a határolók függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. Az alapértelmezett érték true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Megjegyzések

Példa: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Lásd még

* Osztály [IMathDelimiter](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)