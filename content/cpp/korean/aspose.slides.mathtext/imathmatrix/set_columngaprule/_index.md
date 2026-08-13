---
title: set_ColumnGapRule()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "행렬의 열 사이의 수평 간격 유형; 수평 간격 단위는 ems 또는 points(트윕스로 저장됩니다). 기본값: SingleSpacingGap (0)"
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) 메서드


행렬의 열 사이의 수평 간격 유형; 수평 간격 단위는 ems 또는 points(트윕스로 저장됩니다). 기본값: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## 비고


예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 참조

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)