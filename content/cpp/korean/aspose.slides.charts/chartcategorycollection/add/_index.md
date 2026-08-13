---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에 카테고리가 존재하면 반환합니다. 그렇지 않으면 IChartDataCell에서 새 차트 카테고리를 생성하고 컬렉션에 추가합니다.
type: docs
weight: 92
url: /ko/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) 메서드

컬렉션에 카테고리가 존재하면 반환합니다. 그렇지 않으면 [IChartDataCell](../../ichartdatacell/)에서 새로운 차트 카테고리를 생성하여 컬렉션에 추가합니다.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/)은(는) 차트 카테고리를 생성하는 데 사용됩니다. |

### 반환값

추가된 카테고리 또는 기존 카테고리.

## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) 메서드

값으로부터 새로운 [ChartCategory](../../chartcategory/)을 생성하고 컬렉션에 추가합니다.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 값. |

### 반환값

추가된 [IChartCategory](../../ichartcategory/).

## 비고

이 메서드는 이름이 AUTO_DATA인 워크시트를 추가하고 그곳에 모든 값을 추가합니다. [ChartDataWorkbook](../../chartdataworkbook/)을(를) 사용하여 셀 값을 추가하거나 편집할 경우, 이 워크시트를 사용하지 않도록 하십시오. 이 메서드를 사용하여 추가되는 값의 최대 수는 16,711,680을 초과할 수 없습니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartCategory](../../ichartcategory/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [ChartCategoryCollection](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)