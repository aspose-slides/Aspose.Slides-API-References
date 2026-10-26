---
title: get_Categories()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengambil kategori utama (atau baik kategori utama maupun sekunder jika IChartData::set_UseSecondaryCategories diatur ke false). Hanya-baca IChartCategoryCollection."
type: docs
weight: 40
url: /id/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() metode

Mengambil kategori utama (atau baik kategori utama maupun sekunder jika [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke false). Hanya-baca [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Catatan

Jika [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke false maka [IChartData::get_SecondaryCategories](../get_secondarycategories/) mengembalikan null dan data dalam [IChartData::get_Categories](./) digunakan untuk seri utama dan sekunder. Jika [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke true maka data dalam [IChartData::get_SecondaryCategories](../get_secondarycategories/) digunakan untuk seri sekunder dan data dalam [IChartData::get_Categories](./) digunakan untuk seri utama. 

Contoh. Kategori apa yang terkait dengan seri - ChartData.Categories atau ChartData.SecondaryCategories? 
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

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartCategoryCollection](../../ichartcategorycollection/)
* Kelas [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)