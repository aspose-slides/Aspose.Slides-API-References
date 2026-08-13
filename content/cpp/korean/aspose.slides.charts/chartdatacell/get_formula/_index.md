---
title: get_Formula()
second_title: C++용 Aspose.Slides API 레퍼런스
description: A1 스타일의 수식을 가져옵니다.
type: docs
weight: 53
url: /ko/aspose.slides.charts/chartdatacell/get_formula/
---
## ChartDataCell::get_Formula() 메서드


A1 스타일의 수식을 가져옵니다.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_Formula() override
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