---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "행렬의 열 사이에 있는 수평 간격 유형입니다; 수평 간격 단위는 ems 또는 points(트윕스로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)"
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() 메서드


행렬의 열 사이에 있는 수평 간격 유형입니다; 수평 간격 단위는 ems 또는 points(트윕스로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## 비고


예시:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 참조

* 열거형 [MathSpacingRules](../../mathspacingrules/)
* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)