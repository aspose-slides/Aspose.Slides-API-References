---
title: set_BeginningCharacter()
second_title: Aspose.Slides pro C++ – reference API
description: "Delimiter Beginning Character určuje počáteční nebo otevírací znak oddělovače. Matematické oddělovače jsou uzavírací znaky, jako jsou kulaté závorky, hranaté závorky a složené závorky. Výchozí: '('."
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) metoda


Delimiter Beginning Character určuje počáteční, nebo otevírací, znak oddělovače. Matematické oddělovače jsou uzavírací znaky, jako jsou kulaté závorky, hranaté závorky a složené závorky. Výchozí: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
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