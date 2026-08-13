---
title: set_R1C1Formula()
second_title: Aspose.Slides for C++ API 참조
description: R1C1 스타일로 수식을 설정합니다.
type: docs
weight: 92
url: /ko/aspose.slides.charts/chartdatacell/set_r1c1formula/
---
## ChartDataCell::set_R1C1Formula(System::String) 메서드

R1C1 스타일로 수식을 설정합니다.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_R1C1Formula(System::String value) override
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