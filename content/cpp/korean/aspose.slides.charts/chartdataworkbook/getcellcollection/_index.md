---
title: GetCellCollection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 셀 집합을 가져옵니다.
type: docs
weight: 14
url: /ko/aspose.slides.charts/chartdataworkbook/getcellcollection/
---
## ChartDataWorkbook::GetCellCollection(System::String, bool) 메서드

셀 집합을 가져옵니다.

```cpp
System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::ChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) formula와 같은 "Sheet1!$A$2:$A$5". |
| skipHiddenCells | **bool** | true이면 메서드는 숨겨진 셀 없이 컬렉션을 반환합니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Class [ChartDataWorkbook](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)