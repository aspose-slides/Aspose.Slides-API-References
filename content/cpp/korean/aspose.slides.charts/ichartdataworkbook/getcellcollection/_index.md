---
title: GetCellCollection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 셀 집합을 가져옵니다.
type: docs
weight: 27
url: /ko/aspose.slides.charts/ichartdataworkbook/getcellcollection/
---
## IChartDataWorkbook::GetCellCollection(System::String, bool) 메서드

셀 집합을 가져옵니다.

```cpp
virtual System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::IChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) \"Sheet1!$A$2:$A$5\"와 같은 수식. |
| skipHiddenCells | **bool** | true이면 메서드는 숨겨진 셀 없이 컬렉션을 반환합니다. |

### 반환 값

셀 집합 [IChartCellCollection](../../ichartcellcollection/)

## 추가 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartCellCollection](../../ichartcellcollection/)
* 클래스 [String](../../../system/string/)
* 클래스 [IChartDataWorkbook](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)