---
title: set_DelimiterShape()
second_title: Aspose.Slides для C++ справочника API
description: "Указывает форму разделителей в объекте разделителя. Когда указано MathDelimiterShape::Centered, разделители центрируются относительно математической оси математического текста и при этом масштабируются так, чтобы полностью охватывать высоту их содержимого. Когда указано MathDelimiterShape::Match, их высота и форма изменяются, точно соответствуя содержимому."
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) метод


Указывает форму разделителей в объекте разделителя. Когда [MathDelimiterShape::Centered](../../mathdelimitershape/), разделители центрируются относительно математической оси математического текста и при этом масштабируются так, чтобы полностью охватывать высоту их содержимого. Когда [MathDelimiterShape::Match](../../mathdelimitershape/), их высота и форма изменяются, точно соответствуя содержимому.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Примечания


Пример: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## См. также

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Класс [MathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)