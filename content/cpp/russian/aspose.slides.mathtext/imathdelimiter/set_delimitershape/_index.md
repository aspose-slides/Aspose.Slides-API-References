---
title: set_DelimiterShape()
second_title: Aspose.Slides для C++ справочник API
description: "Задает форму разделителей в объекте разделителя. Когда установлено MathDelimiterShape::Centered, разделители центрируются вокруг математической оси текста и при этом масштабируются так, чтобы охватывать всю высоту их содержимого. Когда установлено MathDelimiterShape::Match, их высота и форма изменяются так, чтобы точно соответствовать их содержимому."
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) метод

Указывает форму разделителей в объекте разделителя. Когда установлено [MathDelimiterShape::Centered](../../mathdelimitershape/), разделители центрируются вокруг математической оси текста и при этом подгоняются так, чтобы охватывать всю высоту их содержимого. Когда установлено [MathDelimiterShape::Match](../../mathdelimitershape/), их высота и форма изменяются так, чтобы точно соответствовать их содержимому.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Примечания

Пример: ```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## См. также

* Перечисление [MathDelimiterShape](../../mathdelimitershape/)
* Класс [IMathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)