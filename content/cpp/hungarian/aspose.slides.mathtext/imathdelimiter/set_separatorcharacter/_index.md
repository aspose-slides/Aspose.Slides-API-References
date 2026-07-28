---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API Referenciája
description: "A Delimiter Separator Character megadja azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Alapértelmezett: '|'."
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) metódus

A Delimiter Separator Character megadja azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Az alapértelmezett: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Megjegyzések

Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Lásd még

* Osztály [IMathDelimiter](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)