---
title: get_DelimiterShape()
second_title: Справочник API Aspose.Slides для C++
description: "Указывает форму разделителей в объекте разделителя. Когда MathDelimiterShape::Centered, разделители центрируются вокруг математической оси текста и могут быть изменены так, чтобы соответствовать полной высоте их содержимого. Когда MathDelimiterShape::Match, их высота и форма изменяются так, чтобы точно соответствовать их содержимому."
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() метод


Указывает форму разделителей в объекте разделителя. Когда [MathDelimiterShape::Centered](../../mathdelimitershape/), разделители центрируются вокруг математической оси текста и могут быть изменены, чтобы соответствовать полной высоте их содержимого. Когда [MathDelimiterShape::Match](../../mathdelimitershape/), их высота и форма изменяются так, чтобы точно соответствовать их содержимому.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Примечания


Пример: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## См. также

* Перечисление [MathDelimiterShape](../../mathdelimitershape/)
* Класс [IMathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)