---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "false 로 설정하면 IChartData::get_SecondaryCategories는 null을 반환하고 IChartData::get_Categories의 데이터는 기본 및 보조 시리즈 모두에 사용됩니다. true 로 설정하면 IChartData::get_SecondaryCategories의 데이터는 보조 시리즈에 사용되고 IChartData::get_Categories의 데이터는 기본 시리즈에 사용됩니다. bool을 반환합니다."
type: docs
weight: 53
url: /ko/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() 메서드

If false 로 설정하면 [IChartData::get_SecondaryCategories](../get_secondarycategories/)는 null을 반환하고 [IChartData::get_Categories](../get_categories/)의 데이터는 기본 시리즈와 보조 시리즈 모두에 사용됩니다. true 로 설정하면 [IChartData::get_SecondaryCategories](../get_secondarycategories/)의 데이터는 보조 시리즈에 사용되고 [IChartData::get_Categories](../get_categories/)의 데이터는 기본 시리즈에 사용됩니다. 읽기 **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## 비고

예시. What categories are related to series - ChartData.Categories or ChartData.SecondaryCategories?
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

* 클래스 [IChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)