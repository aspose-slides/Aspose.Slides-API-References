---
title: set_BeginningCharacter()
second_title: Справочник API Aspose.Slides для C++
description: "Начальный символ-разделитель задаёт начальный, или открывающий, символ разделителя. Математические разделители — это ограничивающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: '('."
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) метод

Delimiter Beginning Character указывает начальный, или открывающий, символ-разделитель. Математические разделители — это ограничивающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## Примечания


Пример: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Смотрите также

* Класс [MathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)