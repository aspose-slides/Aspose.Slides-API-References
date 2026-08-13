---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에 카테고리가 존재하면 이를 반환합니다. 그렇지 않으면 IChartDataCell에서 새 차트 카테고리를 생성하고 컬렉션에 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) method

컬렉션에 카테고리가 존재하면 이를 반환합니다. 그렇지 않으면 [IChartDataCell](../../ichartdatacell/)에서 새 차트 카테고리를 만들고 컬렉션에 추가합니다.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/)는 차트 카테고리를 생성하는 데 사용됩니다. |

### 반환값

추가된 카테고리 또는 기존 카테고리.

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) method

값으로부터 새로운 [IChartCategory](../../ichartcategory/)를 생성하고 컬렉션에 추가합니다.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 값. |

### 반환값

추가된 [IChartCategory](../../ichartcategory/).

## 비고

이 메서드는 AUTO_DATA라는 이름의 워크시트를 추가하고 모든 값을 그곳에 넣습니다. [IChartDataWorkbook](../../ichartdataworkbook/)를 사용하여 셀 값을 추가하거나 편집하는 경우, 이 워크시트를 사용하지 않도록 하세요. 이 메서드를 사용하여 추가되는 값의 최대 수는 16711680을 초과해서는 안 됩니다.

## 관련 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)