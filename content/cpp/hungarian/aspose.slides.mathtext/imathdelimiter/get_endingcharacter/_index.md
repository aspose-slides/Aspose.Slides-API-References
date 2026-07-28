---
title: get_EndingCharacter()
second_title: "Aspose.Slides C++ API referencia"
description: "A Delimiter Ending Character meghatározza a záró, vagy befejező delimiter karaktert. A matematikai delimiter karakterek olyan befoglaló jelek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: ')'."
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() metódus

A Delimiter Ending Character meghatározza a záró, vagy lezáró delimiter karaktert. A matematikai delimiter karakterek olyan befoglaló jelek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Az alapértelmezett: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
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