---
title: get_BaseJustification()
second_title: Aspose.Slides для C++ API Reference
description: "Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней или центральной части объекта массива. Значение по умолчанию: Center"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() метод


Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней или центральной части объекта массива. Значение по умолчанию: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Примечания


Пример: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## См. также

* Перечисление [MathVerticalAlignment](../../mathverticalalignment/)
* Класс [IMathArray](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)