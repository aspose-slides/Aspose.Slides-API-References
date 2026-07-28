---
title: get_SeparatorCharacter()
second_title: Aspose.Slides for C++ API hivatkozás
description: "A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Alapértelmezett: '|'."
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() metódus


Delimiter Separator Character megadja azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Alapértelmezett: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Megjegyzések


Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Lásd még

* Osztály [IMathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)