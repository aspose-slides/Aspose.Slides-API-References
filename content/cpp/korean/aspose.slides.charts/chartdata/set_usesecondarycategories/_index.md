---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API 참조
description: "false로 설정하면 ChartData::get_SecondaryCategories가 null을 반환하고 ChartData::get_Categories의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true로 설정하면 ChartData::get_SecondaryCategories의 데이터가 보조 시리즈에 사용되고 ChartData::get_Categories의 데이터가 기본 시리즈에 사용됩니다. bool를 작성합니다."
type: docs
weight: 66
url: /ko/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) method


false로 설정하면 [ChartData::get_SecondaryCategories](../get_secondarycategories/)가 null을 반환하고 [ChartData::get_Categories](../get_categories/)의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다. true로 설정하면 [ChartData::get_SecondaryCategories](../get_secondarycategories/)의 데이터가 보조 시리즈에 사용되고 [ChartData::get_Categories](../get_categories/)의 데이터가 기본 시리즈에 사용됩니다. **bool**를 작성합니다.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## 비고


예시. 어떤 카테고리가 시리즈와 관련이 있나요 - [ChartData::get_Categories](../get_categories/) 또는 [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* 클래스 [ChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)