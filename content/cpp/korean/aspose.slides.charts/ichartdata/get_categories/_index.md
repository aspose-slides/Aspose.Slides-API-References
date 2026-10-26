---
title: get_Categories()
second_title: Aspose.Slides for C++ API 참조
description: "기본 카테고리를 가져옵니다 (또는 IChartData::set_UseSecondaryCategories가 false로 설정된 경우 기본 및 보조 카테고스를 모두 가져옵니다). 읽기 전용 IChartCategoryCollection."
type: docs
weight: 40
url: /ko/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() 메서드

기본 카테고리를 가져옵니다 (또는 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/)가 false로 설정된 경우 기본 및 보조 카테고리를 모두 가져옵니다). 읽기 전용 [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## 비고

만약 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/)가 false로 설정되면 [IChartData::get_SecondaryCategories](../get_secondarycategories/)는 null을 반환하고 [IChartData::get_Categories](./)의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. 만약 [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/)가 true로 설정되면 [IChartData::get_SecondaryCategories](../get_secondarycategories/)의 데이터는 보조 시리즈에 사용되고 [IChartData::get_Categories](./)의 데이터는 기본 시리즈에 사용됩니다.

예시. 시리즈와 관련된 카테고리는 무엇입니까 - ChartData.Categories 또는 ChartData.SecondaryCategories?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // 관련 카테고리는 series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // 관련 카테고리는 series->get_Chart()->get_ChartData()->get_Categories()
}
```

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartCategoryCollection](../../ichartcategorycollection/)
* 클래스 [IChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)