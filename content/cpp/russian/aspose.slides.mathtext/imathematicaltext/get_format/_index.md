---
title: get_Format()
second_title: Справочник API Aspose.Slides для C++
description: Свойства форматирования текста
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() метод


Свойства форматирования текста

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## Примечания


Пример: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IPortionFormat](../../../aspose.slides/iportionformat/)
* Класс [IMathematicalText](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)