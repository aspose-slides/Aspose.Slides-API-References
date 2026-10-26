---
title: set_SeparatorCharacter()
second_title: Справочник API Aspose.Slides для C++
description: "Delimiter Separator Character указывает символ, который разделяет аргументы в объекте delimiter. По умолчанию: '|'."
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) метод

Delimiter Separator Character указывает символ, который разделяет аргументы в объекте delimiter. По умолчанию: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Примечания

Пример: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## См. также

* Класс [MathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)