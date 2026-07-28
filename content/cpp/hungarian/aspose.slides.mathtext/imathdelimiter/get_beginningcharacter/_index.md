---
title: get_BeginningCharacter()
second_title: Aspose.Slides C++ API referencia
description: "A Delimiter Beginning Character meghatározza a kezdő vagy nyitó elválasztó karaktert. A matematikai elválasztók olyan záró karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett érték: '('."
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() metódus


Delimiter Beginning Character meghatározza a kezdő, vagy nyitó, elválasztó karaktert. A matematikai elválasztók olyan záró karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett érték: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Megjegyzések


Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Lásd még

* Osztály [IMathDelimiter](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)