---
title: get_DelimiterShape()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "구분자 객체에서 구분자의 모양을 지정합니다. MathDelimiterShape::Centered인 경우, 구분자는 수학 텍스트의 수학 축을 중심으로 배치되며 내용 전체 높이에 맞게 조정됩니다. MathDelimiterShape::Match인 경우, 높이와 모양이 내용에 정확히 일치하도록 변경됩니다."
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() 메서드

구분자 객체에서 구분자의 모양을 지정합니다. [MathDelimiterShape::Centered](../../mathdelimitershape/)인 경우, 구분자는 수학 텍스트의 수학 축을 중심으로 배치되며 내용 전체 높이에 맞추어 조정됩니다. [MathDelimiterShape::Match](../../mathdelimitershape/)인 경우, 높이와 모양이 내용에 정확히 맞도록 변경됩니다.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## 비고

예:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 참조

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* 클래스 [IMathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)