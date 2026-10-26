---
title: get_BeginningCharacter()
second_title: Справочник API Aspose.Slides для C++
description: "Символ начала разделителя указывает начальный, или открывающий, символ-разделитель. Математические разделители — это охватывающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: '('."
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() метод

Delimiter Beginning Character указывает начальный, или открывающий, символ-разделитель. Математические разделители — это охватывающие символы, такие как скобки, квадратные скобки и фигурные скобки. По умолчанию: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Примечания

Пример:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## См. также

* Класс [MathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)