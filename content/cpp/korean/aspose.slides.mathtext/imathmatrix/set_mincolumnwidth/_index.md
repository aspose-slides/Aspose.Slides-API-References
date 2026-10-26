---
title: set_MinColumnWidth()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "twips(포인트의 1/20) 단위로 지정된 최소 열 너비. (또는 \\u201CColumn Gap\\u201D 또는 \\u201CGap Width\\u201D라고도 함) 간격이 MinColumnWidth에 추가되어 전체 Matrix Column Spacing(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0."
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) 메서드

twips(포인트의 1/20) 단위로 지정된 최소 열 너비. (또는 “Column Gap” 또는 “Gap Width”라고도 함) 간격은 MinColumnWidth에 추가되어 전체 Matrix [Column](../../../aspose.slides/column/) Spacing(다른 열의 동일한 가장자리 사이 거리)을 결정합니다. 기본값: 0.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
```

## 비고

예시: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 참고

* 클래스 [IMathMatrix](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)