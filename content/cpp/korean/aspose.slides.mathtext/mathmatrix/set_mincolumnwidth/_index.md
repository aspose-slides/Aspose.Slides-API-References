---
title: set_MinColumnWidth()
second_title: Aspose.Slides for C++ API 참조
description: "트윕(포인트의 1/20) 단위 최소 열 너비입니다. 간격(\\u201CColumn Gap\\u201D 또는 \\u201CGap Width\\u201D라고도 함)은 MinColumnWidth에 추가되어 전체 Matrix Column Spacing(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0."
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/mathmatrix/set_mincolumnwidth/
---
## MathMatrix::set_MinColumnWidth(uint32_t) method

트윕(포인트의 1/20) 단위 최소 열 너비입니다. 간격(“Column Gap” 또는 “Gap Width”라고도 함)은 MinColumnWidth에 추가되어 전체 Matrix [Column](../../../aspose.slides/column/) 간격(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0.

```cpp
void Aspose::Slides::MathText::MathMatrix::set_MinColumnWidth(uint32_t value) override
```

## 비고

예시:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 참조

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)