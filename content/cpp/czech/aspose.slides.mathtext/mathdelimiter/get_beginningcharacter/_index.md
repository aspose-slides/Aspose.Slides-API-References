---
title: get_BeginningCharacter()
second_title: Aspose.Slides pro C++ API Reference
description: "Delimiter Beginning Character specifikuje počátek, nebo otevírací znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: '('."
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() metoda

Delimiter Beginning Character specifikuje počátek, nebo otevírací, znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Poznámky


Příklad: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Viz také

* Třída [MathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)