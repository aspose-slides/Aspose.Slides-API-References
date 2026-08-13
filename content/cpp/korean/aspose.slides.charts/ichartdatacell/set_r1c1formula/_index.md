---
title: set_R1C1Formula()
second_title: Aspose.Slides C++용 API 참조
description: R1C1 스타일로 수식을 설정합니다.
type: docs
weight: 92
url: /ko/aspose.slides.charts/ichartdatacell/set_r1c1formula/
---
## IChartDataCell::set_R1C1Formula(System::String) 메서드


R1C1 스타일로 수식을 설정합니다.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_R1C1Formula(System::String value)=0
```

## 비고



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [IChartDataCell](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)