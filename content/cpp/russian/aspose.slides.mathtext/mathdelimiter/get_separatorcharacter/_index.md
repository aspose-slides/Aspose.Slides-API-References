---
title: get_SeparatorCharacter()
second_title: Справочник API Aspose.Slides для C++
description: "Delimiter Separator Character задает символ, который разделяет аргументы в объекте разделителя. По умолчанию: '|'."
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() метод

Delimiter Separator Character задает символ, который разделяет аргументы в объекте разделителя. По умолчанию: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
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