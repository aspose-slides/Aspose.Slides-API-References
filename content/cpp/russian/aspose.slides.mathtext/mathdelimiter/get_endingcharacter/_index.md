---
title: get_EndingCharacter()
second_title: Aspose.Slides для C++ — справочник API
description: "Delimiter Ending Character указывает завершающий, или закрывающий, символ-делимитер. Математические разделители — это ограничивающие символы, такие как круглые скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'."
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() метод

Delimiter Ending Character указывает завершающий, или закрывающий, символ-делимитер. Математические разделители — это ограничивающие символы, такие как круглые скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Примечания

Пример:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## См. также

* Класс [MathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)