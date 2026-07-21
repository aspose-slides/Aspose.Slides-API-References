---
title: set_SeparatorCharacter()
second_title: Aspose.Slides для C++ API Reference
description: "Символ-разделитель указывает символ, который отделяет аргументы в объекте разделителя. По умолчанию: '|'."
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) method

Delimiter Separator Character указывает символ, который отделяет аргументы в объекте разделителя. По умолчанию: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Примечания

Пример: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## См. также

* Класс [IMathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)