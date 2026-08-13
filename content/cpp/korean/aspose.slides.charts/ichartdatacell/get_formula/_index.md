---
title: get_Formula()
second_title: Aspose.Slides for C++ API 참조
description: A1 스타일의 수식을 가져옵니다.
type: docs
weight: 53
url: /ko/aspose.slides.charts/ichartdatacell/get_formula/
---
## IChartDataCell::get_Formula() 메서드

A1 스타일의 수식을 가져옵니다.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_Formula()=0
```

## 비고



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [IChartDataCell](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)