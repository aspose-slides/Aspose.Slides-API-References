---
title: get_HideRight()
second_title: Справочник API Aspose.Slides для C++
description: Скрывать правый край (по умолчанию false) — указывает, скрыт или отображён правый край рамки.
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/imathborderbox/get_hideright/
---
## IMathBorderBox::get_HideRight() метод


Hide Right Edge (default is false) - указывает, скрыт ли или отображён правый край рамки.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideRight()=0
```

## Примечания


Пример: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideRight(true);
```

## См. также

* Класс [IMathBorderBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)