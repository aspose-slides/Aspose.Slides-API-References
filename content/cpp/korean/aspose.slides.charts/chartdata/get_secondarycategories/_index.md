---
title: get_SecondaryCategories()
second_title: Aspose.Slides for C++ API 참조
description: "ChartData::get_UseSecondaryCategories가 true인 경우 보조 카테고리를 가져옵니다. 읽기 전용 IChartCategoryCollection."
type: docs
weight: 79
url: /ko/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() 메서드

[ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/)가 true인 경우 보조 카테고리를 가져옵니다. 읽기 전용 [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## 비고

[ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/)가 false로 설정된 경우 [ChartData::get_SecondaryCategories](./)는 null을 반환하고 [ChartData::get_Categories](../get_categories/)의 데이터는 기본 시리즈와 보조 시리즈 모두에 사용됩니다. [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/)가 true로 설정된 경우 [ChartData::get_SecondaryCategories](./)의 데이터는 보조 시리즈에, [ChartData::get_Categories](../get_categories/)의 데이터는 기본 시리즈에 사용됩니다.

예시. 어떤 카테고리가 시리즈와 관련이 있습니까 - [ChartData::get_Categories](../get_categories/) 또는 [ChartData::get_SecondaryCategories](./)?
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

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartCategoryCollection](../../ichartcategorycollection/)
* 클래스 [ChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)