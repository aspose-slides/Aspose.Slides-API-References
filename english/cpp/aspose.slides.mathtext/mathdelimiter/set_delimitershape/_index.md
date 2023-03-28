---
title: set_DelimiterShape()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape::Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape::Match, their height and shape are altered to exactly match their contents."
type: docs
weight: 131
url: /cpp/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape([MathDelimiterShape](../../mathdelimitershape/)) method


Specifies the shape of delimiters in the delimiter object. When is [MathDelimiterShape::Centered](../../mathdelimitershape/), delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is [MathDelimiterShape::Match](../../mathdelimitershape/), their height and shape are altered to exactly match their contents.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Remarks


Example: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## See Also

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
