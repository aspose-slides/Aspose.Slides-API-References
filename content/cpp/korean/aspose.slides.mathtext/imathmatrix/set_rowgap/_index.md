---
title: set_RowGap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "행렬의 행 사이의 수직 간격 값; RowGapRule이 3 (\"Exactly\")으로 설정된 경우 단위는 twip(포인트의 1/20)으로 해석됩니다. RowGapRule이 4 (\"Multiple\")으로 설정된 경우 단위는 반줄로 해석됩니다. 기본값: 0"
type: docs
weight: 196
url: /ko/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) 메서드

행렬의 행 사이의 수직 간격 값입니다; RowGapRule이 3(\"Exactly\")으로 설정된 경우 단위는 twip(포인트의 1/20)으로 해석됩니다. RowGapRule이 4(\"Multiple\")으로 설정된 경우 단위는 반줄로 해석됩니다. 기본값: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
```

## 비고

예:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## 또 보기

* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)