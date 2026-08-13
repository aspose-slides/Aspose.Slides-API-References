---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API 참조
description: "false 로 설정하면 IChartData::get_SecondaryCategories 가 null을 반환하고 IChartData::get_Categories 의 데이터가 기본 시리즈와 보조 시리즈 모두에 사용됩니다. true 로 설정하면 IChartData::get_SecondaryCategories 의 데이터가 보조 시리즈에 사용되고 IChartData::get_Categories 의 데이터가 기본 시리즈에 사용됩니다. bool 를 작성하십시오."
type: docs
weight: 66
url: /ko/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) 메서드


false 로 설정하면 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 가 null을 반환하고 [IChartData::get_Categories](../get_categories/) 의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true 로 설정하면 [IChartData::get_SecondaryCategories](../get_secondarycategories/) 의 데이터가 보조 시리즈에 사용되고 [IChartData::get_Categories](../get_categories/) 의 데이터가 기본 시리즈에 사용됩니다. **bool** 를 작성하십시오.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## 비고


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

* 클래스 [IChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)