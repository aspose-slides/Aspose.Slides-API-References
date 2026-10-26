---
title: set_EndingCharacter()
second_title: Aspose.Slides C++ API Referencia
description: "A Delimiter Ending Character meghatározza a befejező vagy záró elválasztó karaktert. A matematikai elválasztók olyan befoglaló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: ')'."
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) metódus


Delimiter Ending Character meghatározza a befejező, vagy záró, elválasztó karaktert. A matematikai elválasztók olyan befoglaló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## Megjegyzések


Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Lásd még

* Osztály [MathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)