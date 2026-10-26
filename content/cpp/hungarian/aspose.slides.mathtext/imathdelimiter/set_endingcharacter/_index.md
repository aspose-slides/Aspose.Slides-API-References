---
title: set_EndingCharacter()
second_title: Aspose.Slides C++ API hivatkozás
description: "Az elválasztó záró karaktere meghatározza a befejező vagy záró elválasztó karaktert. A matematikai elválasztók befoglaló karakterek, mint a zárójelek, a szögletes zárójelek és a kapcsos zárójelek. Az alapértelmezett: ')'."
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) metódus


A Delimiter Ending Character megadja a befejező vagy záró elválasztó karaktert. A matematikai elválasztók olyan befoglaló karakterek, mint a zárójelek, a szögletes zárójelek és a kapcsos zárójelek. Az alapértelmezett: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Megjegyzések


Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Lásd még

* Osztály [IMathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)