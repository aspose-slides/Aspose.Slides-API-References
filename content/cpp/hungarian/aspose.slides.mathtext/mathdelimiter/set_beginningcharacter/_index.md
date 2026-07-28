---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API Referencia
description: "A Delimiter Beginning Character meghatározza a kezdő, vagy nyitó elválasztó karaktert. A matematikai elválasztók olyan záró karakterek, mint a zárójelek, a szögletes zárójelek és a kapcsos zárójelek. Alapértelmezett: '('."
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) metódus


A Delimiter Beginning Character meghatározza a kezdő, vagy nyitó elválasztó karaktert. A matematikai elválasztók olyan záró karakterek, mint a zárójelek, a szögletes zárójelek és a kapcsos zárójelek. Alapértelmezett: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## Megjegyzés


Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Lásd még

* Osztály [MathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)