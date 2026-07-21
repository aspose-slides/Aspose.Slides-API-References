---
title: get_ExplicitBreak()
second_title: Справка API Aspose.Slides для C++
description: "Explicit break указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта box. Указывает номер оператора в предыдущей строке математического текста, который будет использоваться в качестве точки выравнивания для текущей строки математического текста. Возможные значения: 1..255. По умолчанию: 0 (нет явного переноса)."
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() метод

Explicit break указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта Box. Указывает номер оператора в предыдущей строке математического текста, который будет использован в качестве точки выравнивания для текущей строки математического текста. Возможные значения: 1..255 По умолчанию: 0 (нет явного переноса)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## Замечания

Пример:

```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## См. также

* Класс [MathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)