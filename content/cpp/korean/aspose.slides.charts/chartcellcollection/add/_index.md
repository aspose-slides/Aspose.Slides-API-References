---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에 새 셀을 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) method

컬렉션에 새 셀을 추가합니다.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 추가할 새 셀. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) method

지정된 값으로 [ChartDataCell](../../chartdatacell/)를 만들고 컬렉션에 추가합니다.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 값. |
## 비고

이 메서드는 이름이 AUTO_DATA인 워크시트를 추가하고 그곳에 모든 값을 추가합니다. [ChartDataWorkbook](../../chartdataworkbook/)를 사용하여 [Cell](../../../aspose.slides/cell/) 값을 추가하거나 편집하는 경우 이 워크시트를 사용하지 않도록 하십시오. 이 메서드를 사용하여 추가되는 값의 최대 개수는 16711680을 초과할 수 없습니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [ChartCellCollection](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)