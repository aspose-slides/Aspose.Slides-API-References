---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "행렬의 열 사이의 수평 간격 유형; 수평 간격 단위는 em 또는 포인트(twips 단위)일 수 있습니다. 기본값: SingleSpacingGap (0)"
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() 메서


행렬의 열 사이의 수평 간격 유형입니다. 수평 간격 단위는 em 또는 포인트(twips 단위)일 수 있습니다. 기본값: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## 비고


예시: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 참조

* Enum [MathSpacingRules](../../mathspacingrules/)
* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)