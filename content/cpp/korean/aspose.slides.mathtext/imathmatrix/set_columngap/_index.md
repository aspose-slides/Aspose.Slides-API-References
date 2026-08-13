---
title: set_ColumnGap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "행렬의 열 사이의 가로 간격 값; ColumnGapRule이 3 (\"Exactly\")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. ColumnGapRule이 4 (\"Multiple\")으로 설정된 경우 단위는 0.5 em 증분 수로 해석됩니다. 다른 경우는 무시됩니다. 기본값: 0"
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) 메서드


행렬의 열 사이의 가로 간격 값; ColumnGapRule이 3 ("Exactly")으로 설정된 경우 단위는 twips(포인트의 1/20)로 해석됩니다. ColumnGapRule이 4 ("Multiple")으로 설정된 경우 단위는 0.5 em 증분 수로 해석됩니다. 다른 경우는 무시됩니다. 기본값: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## 비고


예제:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## 참고

* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)