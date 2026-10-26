---
title: set_ColumnGap()
second_title: Aspose.Slides for C++ API 참조
description: "행렬의 열 사이의 수평 간격 값; ColumnGapRule이 3 (\"Exactly\")으로 설정된 경우, 단위는 twips(포인트의 1/20)로 해석됩니다. ColumnGapRule이 4 (\"Multiple\")으로 설정된 경우, 단위는 0.5 em 증가 단위의 개수로 해석됩니다. 다른 경우는 무시됩니다. 기본값: 0"
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) 메서드

행렬 열 사이의 수평 간격 값; ColumnGapRule이 3("Exactly")으로 설정된 경우, 단위는 twips(포인트의 1/20)로 해석됩니다. ColumnGapRule이 4("Multiple")으로 설정된 경우, 단위는 0.5 em 증가 단위의 개수로 해석됩니다. 다른 경우는 무시됩니다. 기본값: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
```

## 비고

예:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## 관련 항목

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)