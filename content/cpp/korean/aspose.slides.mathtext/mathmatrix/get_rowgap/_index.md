---
title: get_RowGap()
second_title: Aspose.Slides for C++ API 참조
description: "행 매트릭스의 행 사이의 수직 간격 값; RowGapRule이 3 (\"Exactly\")으로 설정된 경우 단위는 twips (포인트의 1/20) 로 해석됩니다. RowGapRule이 4 (\"Multiple\")으로 설정된 경우 단위는 half-lines 로 해석됩니다. 기본값: 0"
type: docs
weight: 183
url: /ko/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() 메서드

행 사이의 수직 간격 값; RowGapRule이 3("Exactly")으로 설정된 경우 단위는 twips (1/20th of a point) 로 해석됩니다. RowGapRule이 4("Multiple")으로 설정된 경우 단위는 half-lines 로 해석됩니다. Default: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## 비고

예제: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## 참고

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)