---
title: get_ExplicitBreak()
second_title: Aspose.Slides для C++ справка API
description: "Explicit break указывает, существует ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта Box. Указывает номер оператора в предыдущей строке математического текста, который будет использоваться в качестве точки выравнивания для текущей строки математического текста. Возможные значения: 1..255. По умолчанию: 0 (нет явного разрыва)."
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() метод

Explicit break указывает, существует ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта Box. Указывает номер оператора в предыдущей строке математического текста, который будет использоваться в качестве точки выравнивания для текущей строки математического текста. Возможные значения: 1..255 По умолчанию: 0 (нет явного разрыва)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Замечания

Пример:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## См. также

* Класс [IMathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)