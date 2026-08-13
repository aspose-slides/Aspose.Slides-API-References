---
title: get_ColumnGap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "행렬의 열 사이 수평 간격 값; ColumnGapRule이 3 (\"Exactly\")으로 설정된 경우, 단위는 twips(1/20 포인트)로 해석됩니다. ColumnGapRule이 4 (\"Multiple\")으로 설정된 경우, 단위는 0.5 em 증가분의 수로 해석됩니다. 다른 경우는 무시됩니다. 기본값: 0"
type: docs
weight: 131
url: /ko/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() 메서드

행렬의 열 사이의 수평 간격 값; ColumnGapRule이 3 (\"Exactly\")으로 설정된 경우, 단위는 twips(1/20 포인트)로 해석됩니다. ColumnGapRule이 4 (\"Multiple\")으로 설정된 경우, 단위는 0.5 em 증가분의 수로 해석됩니다. 다른 경우는 무시됩니다. 기본값: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## 비고

예제: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## 또한 보기

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)