---
title: set_ColumnGapRule()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "행렬의 열 사이의 수평 간격 유형; 수평 간격 단위는 em 또는 포인트(트윕스로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)"
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) 메서드

행렬의 열 사이의 수평 간격 유형; 수평 간격 단위는 em 또는 포인트(트윕스로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## 비고

예시:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 참고

* Enum [MathSpacingRules](../../mathspacingrules/)
* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)