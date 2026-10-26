---
title: get_SeparatorCharacter()
second_title: Справочник API Aspose.Slides для C++
description: "Delimiter Separator Character указывает символ, который разделяет аргументы в объекте разделителя. По умолчанию: '|'."
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() метод


Delimiter Separator Character указывает символ, который разделяет аргументы в объекте разделителя. По умолчанию: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
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