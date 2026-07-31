---
title: get_Categories()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan kategori utama (atau baik kategori utama maupun sekunder jika ChartData::set_UseSecondaryCategories diatur ke false). Hanya-baca IChartCategoryCollection."
type: docs
weight: 40
url: /id/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() method

Mendapatkan kategori utama (atau baik kategori utama maupun sekunder jika [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke false). Hanya-baca [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Catatan

Jika [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke false maka [ChartData::get_SecondaryCategories](../get_secondarycategories/) mengembalikan null dan data dalam [ChartData::get_Categories](./) digunakan baik untuk seri utama maupun sekunder. Jika [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke true maka data dalam [ChartData::get_SecondaryCategories](../get_secondarycategories/) digunakan untuk seri sekunder dan data dalam [ChartData::get_Categories](./) digunakan untuk seri utama.

Contoh. Kategori apa yang terkait dengan seri - [ChartData::get_Categories](./) atau [ChartData::get_SecondaryCategories](../get_secondarycategories/)?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
 // kategori terkait adalah series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
 // kategori terkait adalah series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategoryCollection](../../ichartcategorycollection/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)