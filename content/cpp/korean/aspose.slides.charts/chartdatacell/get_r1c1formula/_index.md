---
title: get_R1C1Formula()
second_title: Aspose.Slides for C++ API 레퍼런스
description: R1C1 스타일의 수식을 가져옵니다.
type: docs
weight: 79
url: /ko/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() 메서드

R1C1 스타일의 수식을 가져옵니다.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## 비고

```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [ChartDataCell](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)