---
title: get_BaseJustification()
second_title: Справочник API Aspose.Slides для C++
description: "Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижнему краю, верхнему краю или по центру объекта массива. Значение по умолчанию: Center"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() метод

Указывает выравнивание массива относительного окружающего текста. Текст за пределами массива может быть выровнен по нижнему краю, верхнему краю или по центру объекта массива. Значение по умолчанию: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Примечания

Пример:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## См. также

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)