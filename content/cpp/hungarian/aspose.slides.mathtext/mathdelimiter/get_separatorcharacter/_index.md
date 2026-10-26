---
title: get_SeparatorCharacter()
second_title: Aspose.Slides C++ API referencia
description: "A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Alapértelmezett: '|'."
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() metódus


Delimiter Separator Character meghatározza a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Alapértelmezett: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## Megjegyzések


Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Lásd még

* Osztály [MathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)