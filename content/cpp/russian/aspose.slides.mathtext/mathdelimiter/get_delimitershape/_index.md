---
title: get_DelimiterShape()
second_title: Справочник API Aspose.Slides для C++
description: "Указывает форму разделителей в объекте разделителя. Когда используется MathDelimiterShape::Centered, разделители центрируются вокруг математической оси текста и при этом масштабируются так, чтобы охватывать всю высоту их содержимого. Когда используется MathDelimiterShape::Match, их высота и форма изменяются, чтобы точно соответствовать их содержимому."
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() method


Указывает форму разделителей в объекте разделителя. Когда [MathDelimiterShape::Centered](../../mathdelimitershape/), разделители центрируются вокруг оси математики математического текста и при этом подгоняются, чтобы охватить всю высоту их содержимого. Когда [MathDelimiterShape::Match](../../mathdelimitershape/), их высота и форма изменяются, чтобы точно соответствовать их содержимому.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Замечания


Пример: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## См. также

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)