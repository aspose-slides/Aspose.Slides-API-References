---
title: get_RowGapRule()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "행렬의 행 사이의 수직 간격 유형; 수직 간격 단위는 줄 또는 포인트(트윕스로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)"
type: docs
weight: 157
url: /ko/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() 메서드

행렬의 행 사이의 수직 간격 유형; 수직 간격 단위는 줄 또는 포인트(트윕스로 저장)일 수 있습니다. 기본값: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## 비고

예:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 관련 항목

* 열거형 [MathSpacingRules](../../mathspacingrules/)
* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)