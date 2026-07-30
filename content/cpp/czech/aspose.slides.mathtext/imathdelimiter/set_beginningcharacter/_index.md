---
title: set_BeginningCharacter()
second_title: Aspose.Slides pro C++ API Reference
description: "Počáteční znak oddělovače určuje počáteční, nebo otevírací znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou kulaté závorky, hranaté závorky a složené závorky. Výchozí hodnota: '('."
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) metoda


Počáteční znak oddělovače určuje počáteční, nebo otevírací znak oddělovače. Matematické oddělovače jsou ohraničující znaky, jako jsou kulaté závorky, hranaté závorky a složené závorky. Výchozí hodnota: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Poznámky


Příklad: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Viz také

* Třída [IMathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)