---
title: get_RowGap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "행렬의 행 사이에 대한 수직 간격 값입니다; RowGapRule이 3 (\"Exactly\")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. RowGapRule이 4 (\"Multiple\")으로 설정된 경우 단위는 반줄로 해석됩니다. 기본값: 0"
type: docs
weight: 183
url: /ko/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() 메서드

행렬의 행 사이에 대한 수직 간격 값입니다; RowGapRule이 3 ("Exactly")로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. RowGapRule이 4 ("Multiple")로 설정된 경우 단위는 반줄로 해석됩니다. 기본값: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## 비고

예제: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## 참고

* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)