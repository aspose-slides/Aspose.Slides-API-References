---
title: set_SeparatorCharacter()
second_title: Aspose.Slides C++ API hivatkozás
description: "A Delimiter Separator Character meghatározza a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. Alapértelmezett: '|'."
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) metódus

Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
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