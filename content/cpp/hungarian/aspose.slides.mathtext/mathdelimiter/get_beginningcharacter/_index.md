---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API-referencia
description: "A Delimiter Beginning Character meghatározza a kezdő, vagy nyitó elválasztó karaktert. A matematikai elválasztók olyan körülvevő karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: '('."
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() metódus


A Delimiter Beginning Character meghatározza a kezdő, vagy nyitó elválasztó karaktert. A matematikai elválasztók olyan körülvevő karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Az alapértelmezett: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Megjegyzések


Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Lásd még

* Osztály [MathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)