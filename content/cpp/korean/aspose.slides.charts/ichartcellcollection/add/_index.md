---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에 새 셀을 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) 메서드

컬렉션에 새 셀을 추가합니다.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 추가할 새 셀입니다. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) 메서드

지정된 값에서 [IChartDataCell](../../ichartdatacell/)을(를) 생성하고 컬렉션에 추가합니다.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 값입니다. |

## 비고

이 메서드는 이름이 AUTO_DATA인 워크시트를 추가하고 모든 값을 해당 워크시트에 추가합니다. [IChartDataWorkbook](../../ichartdataworkbook/)를 사용하여 [Cell](../../../aspose.slides/cell/) 값을 추가하거나 편집하는 경우, 이 워크시트를 사용하지 않아야 합니다. 이 메서드를 사용하여 추가된 값의 최대 수는 16711680을 초과해서는 안 됩니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [IChartCellCollection](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)