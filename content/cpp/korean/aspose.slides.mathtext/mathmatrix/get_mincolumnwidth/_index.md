---
title: get_MinColumnWidth()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "twips(포인트의 1/20) 단위 최소 열 너비입니다. 간격 띄우기(\\u201CColumn Gap\\u201D 또는 \\u201CGap Width\\u201D라고도 함)는 MinColumnWidth에 추가되어 전체 Matrix Column Spacing(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0."
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() 메서드


twips(1포인트의 1/20) 단위의 최소 열 너비입니다. 간격 띄우기(“Column Gap” 또는 “Gap Width”라고도 함)는 MinColumnWidth에 추가되어 전체 Matrix [Column](../../../aspose.slides/column/) Spacing (다른 열의 동일한 가장자리 사이 거리)를 결정합니다. 기본값: 0.

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
```

## 비고


예: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 참고

* 클래스 [MathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)