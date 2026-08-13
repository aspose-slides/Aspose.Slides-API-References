---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "false 로 설정하면 ChartData::get_SecondaryCategories 가 null을 반환하고 ChartData::get_Categories 에 있는 데이터가 기본 시리즈와 보조 시리즈 모두에 사용됩니다. true 로 설정하면 ChartData::get_SecondaryCategories 에 있는 데이터가 보조 시리즈에 사용되고 ChartData::get_Categories 에 있는 데이터가 기본 시리즈에 사용됩니다. bool을 읽습니다."
type: docs
weight: 53
url: /ko/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() 메서드


If set to false then [ChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [ChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If set to true then data in [ChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [ChartData::get_Categories](../get_categories/) is used for primary series. Read **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## 비고


Example. What categories are related to series - [ChartData::get_Categories](../get_categories/) or [ChartData::get_SecondaryCategories](../get_secondarycategories/)?
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