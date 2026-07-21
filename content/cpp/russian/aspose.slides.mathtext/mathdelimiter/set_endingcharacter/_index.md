---
title: set_EndingCharacter()
second_title: Aspose.Slides для C++ справочник API
description: "Символ завершающего разделителя указывает конечный или закрывающий символ разделителя. Математические разделители — это ограничивающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'."
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) метод


Символ завершающего разделителя указывает закрывающий символ разделителя. Математические разделители — это ограничивающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
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