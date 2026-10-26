---
title: set_Formula()
second_title: Aspose.Slides for C++ API 레퍼런스
description: A1 스타일로 수식을 설정합니다.
type: docs
weight: 66
url: /ko/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) 메서드

A1 스타일로 수식을 설정합니다.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## 비고

```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [ChartDataCell](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)