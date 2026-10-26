---
title: get_Categories()
second_title: Aspose.Slides for C++ API 참조
description: "기본 카테고리를 가져옵니다(또는 ChartData::set_UseSecondaryCategories 가 false 로 설정된 경우 기본 및 보조 카테고리를 모두 가져옵니다). 읽기 전용 IChartCategoryCollection."
type: docs
weight: 40
url: /ko/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() 메서드


주 기본 카테고리(또는 [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 가 false 로 설정된 경우 기본 및 보조 카테고리 모두)를 가져옵니다. 읽기 전용 [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## 비고


[ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 가 false 로 설정된 경우 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 은 null 을 반환하고 [ChartData::get_Categories](./) 의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) 가 true 로 설정된 경우 [ChartData::get_SecondaryCategories](../get_secondarycategories/) 의 데이터는 보조 시리즈에, [ChartData::get_Categories](./) 의 데이터는 기본 시리즈에 사용됩니다. 

예시. 어떤 카테고리가 시리즈와 관련이 있나요 - [ChartData::get_Categories](./) 또는 [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartCategoryCollection](../../ichartcategorycollection/)
* 클래스 [ChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)