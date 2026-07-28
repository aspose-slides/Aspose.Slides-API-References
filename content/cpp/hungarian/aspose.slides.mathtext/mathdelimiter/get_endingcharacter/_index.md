---
title: get_EndingCharacter()
second_title: Aspose.Slides C++ API referencia
description: "A Delimiter Ending Character meghatározza a záró, vagy lezáró delimiter karaktert. A matematikai delimitek olyan körülvevő karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Az alapértelmezett: ')'."
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() metódus

A Delimiter Ending Character meghatározza a záró vagy befejező delimiter karaktert. A matematikai delimiterek olyan körülvevő karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Az alapértelmezett: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
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