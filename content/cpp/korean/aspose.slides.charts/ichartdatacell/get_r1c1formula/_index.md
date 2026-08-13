---
title: get_R1C1Formula()
second_title: Aspose.Slides for C++ API 참조
description: R1C1 스타일의 수식을 가져옵니다.
type: docs
weight: 79
url: /ko/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() 메서드


R1C1 스타일의 수식을 가져옵니다.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## 비고



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IChartDataCell](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)