---
title: set_BeginningCharacter()
second_title: Aspose.Slides C++ API referenciája
description: "A Delimiter Beginning Character meghatározza a kezdeti vagy nyitó elválasztó karaktert. A matematikai elválasztók olyan befoglaló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett érték: '('."
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) metódus


Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Megjegyzés


Példa:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Lásd még

* Osztály [IMathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)