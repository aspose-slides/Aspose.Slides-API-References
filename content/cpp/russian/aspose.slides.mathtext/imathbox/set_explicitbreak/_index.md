---
title: set_ExplicitBreak()
second_title: Aspose.Slides для C++ API Reference
description: "Explicit break указывает, есть ли разрыв строки в начале объекта Box, так чтобы строка переносилась в начале объекта box. Указывает номер оператора в предыдущей строке математического текста, который будет использоваться в качестве точки выравнивания для текущей строки математического текста. Возможные значения: 1..255. По умолчанию: 0 (нет явного разрыва)."
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) метод


Explicit break указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта box. Указывает номер оператора в предыдущей строке математического текста, который будет использоваться в качестве точки выравнивания для текущей строки математического текста. Возможные значения: 1..255 По умолчанию: 0 (нет явного разрыва)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
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