---
title: get_EndingCharacter()
second_title: Справочник API Aspose.Slides для C++
description: "Delimiter Ending Character указывает завершающий, или закрывающий, символ-разделитель. Математические разделители — это охватывающие символы, такие как круглые скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'."
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() метод

Delimiter Ending Character указывает завершающий, или закрывающий, символ-разделитель. Математические разделители — это охватывающие символы, такие как круглые скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## Примечания

Пример:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## См. также

* Класс [IMathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)