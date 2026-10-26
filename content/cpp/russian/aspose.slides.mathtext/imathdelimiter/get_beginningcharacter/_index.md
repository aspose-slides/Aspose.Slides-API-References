---
title: get_BeginningCharacter()
second_title: Справочник API Aspose.Slides для C++
description: "Начальный символ-разделитель указывает начало, или открывающий, символ разделителя. Математические разделители — это охватывающие символы, такие как круглые скобки, квадратные скобки и фигурные скобки. Значение по умолчанию: '('."
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() метод

Delimiter Beginning Character указывает начальный, или открывающий, символ-разделитель. Математические разделители — это охватывающие символы, такие как круглые скобки, квадратные скобки и фигурные скобки. Значение по умолчанию: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Примечания

Пример:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## См. также

* Класс [IMathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)