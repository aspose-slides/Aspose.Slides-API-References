---
title: get_Name()
second_title: Справочник API Aspose.Slides для C++
description: Имя функции. Например, имена функций — sin и cos
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() метод

Имя функции. Например, имена функций — sin и cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Примечания

Пример:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathFunction](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)