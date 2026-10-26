---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API 참조
description: "행의 행 사이의 수직 간격 유형; 수직 간격 단위는 줄 또는 포인트(트윕 단위로 저장)입니다. 기본값: SingleSpacingGap (0)"
type: docs
weight: 170
url: /ko/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) 메서드


행 사이의 수직 간격 유형; 수직 간격 단위는 줄 또는 포인트(twip 단위로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## 비고


예:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 참조

* 열거형 [MathSpacingRules](../../mathspacingrules/)
* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)