---
title: set_BaseJustification()
second_title: Aspose.Slides для C++ — справочник API
description: "Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижнему краю, верхнему краю или по центру объекта массива. Значение по умолчанию: Center"
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) метод

Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижнему краю, верхнему краю или по центру объекта массива. Значение по умолчанию: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## Примечания

Пример:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## См. также

* Перечисление [MathVerticalAlignment](../../mathverticalalignment/)
* Класс [MathArray](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)