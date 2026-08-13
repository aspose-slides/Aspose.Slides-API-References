---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "IChartData::get_UseSecondaryCategories가 true인 경우 보조 범주를 가져옵니다. 읽기 전용 IChartCategoryCollection."
type: docs
weight: 79
url: /ko/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() 메서드


[IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/)가 true인 경우 보조 범주를 가져옵니다. 읽기 전용 [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## 비고


[IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/)가 false로 설정된 경우 [IChartData::get_SecondaryCategories](./)는 null을 반환하고 [IChartData::get_Categories](../get_categories/)의 데이터는 기본 및 보조 시리즈 모두에 사용됩니다. [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/)가 true로 설정된 경우 [IChartData::get_SecondaryCategories](./)의 데이터는 보조 시리즈에 사용되고 [IChartData::get_Categories](../get_categories/)의 데이터는 기본 시리즈에 사용됩니다. 

예시. 시리즈와 관련된 범주는 ChartData.Categories 또는 ChartData.SecondaryCategories인가요? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // 관련 범주는 series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // 관련 범주는 series->get_Chart()->get_ChartData()->get_Categories()
}
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartCategoryCollection](../../ichartcategorycollection/)
* 클래스 [IChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)