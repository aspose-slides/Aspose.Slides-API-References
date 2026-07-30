---
title: get_BeginningCharacter()
second_title: Aspose.Slides pro C++ – reference API
description: "Delimiter Beginning Character určuje počáteční, nebo otevírací znak oddělovače. Matematické oddělovače jsou uzavírací znaky, jako jsou kulaté závorky, hranaté závorky a složené závorky. Výchozí hodnota: '('."
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() metoda


Delimiter Beginning Character určuje počáteční, nebo otevírací, znak oddělovače. Matematické oddělovače jsou uzavírací znaky, jako jsou závorky, hranaté závorky a složené závorky. Výchozí hodnota: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
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