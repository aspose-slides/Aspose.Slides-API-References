---
title: get_DelimiterShape()
second_title: Aspose.Slides for C++ API 참조
description: "구분 기호 객체에서 구분 기호의 모양을 지정합니다. MathDelimiterShape::Centered인 경우, 구분 기호는 수학 텍스트의 수학 축을 중심으로 배치되며 내용 전체 높이에 맞게 조정됩니다. MathDelimiterShape::Match인 경우, 구분 기호의 높이와 모양이 내용에 정확히 맞도록 변경됩니다."
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() 메서드


구분 기호 객체에서 구분 기호의 모양을 지정합니다. [MathDelimiterShape::Centered](../../mathdelimitershape/)인 경우, 구분 기호는 수학 텍스트의 수학 축을 중심으로 배치되며 내용 전체 높이에 맞게 조정됩니다. [MathDelimiterShape::Match](../../mathdelimitershape/)인 경우, 구분 기호의 높이와 모양이 내용에 정확히 맞도록 변경됩니다.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## 비고


예: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 참고

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)