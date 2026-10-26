---
title: set_BeginningCharacter()
second_title: Aspose.Slides для C++ справочник API
description: "Delimiter Beginning Character указывает символ начала, или открывающий, разделительный символ. Математические разделители — это окружающие символы, такие как скобки, квадратные скобки и фигурные скобки. Значение по умолчанию: '('."
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) метод


Delimiter Beginning Character указывает символ начала, или открывающий, разделительный символ. Математические разделители — это окружающие символы, такие как скобки, квадратные скобки и фигурные скобки. Значение по умолчанию: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
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