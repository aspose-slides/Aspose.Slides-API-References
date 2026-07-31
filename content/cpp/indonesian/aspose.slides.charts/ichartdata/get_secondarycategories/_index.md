---
title: get_SecondaryCategories()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan kategori sekunder jika IChartData::get_UseSecondaryCategories bernilai true. Hanya baca IChartCategoryCollection."
type: docs
weight: 79
url: /id/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() metode

Mendapatkan kategori sekunder jika [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) bernilai true. Hanya baca [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Keterangan

Jika [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke false maka [IChartData::get_SecondaryCategories](./) mengembalikan null dan data di [IChartData::get_Categories](../get_categories/) digunakan untuk seri primer dan sekunder. Jika [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke true maka data di [IChartData::get_SecondaryCategories](./) digunakan untuk seri sekunder dan data di [IChartData::get_Categories](../get_categories/) digunakan untuk seri primer.

Contoh. Kategori apa yang terkait dengan seri - ChartData.Categories atau ChartData.SecondaryCategories?
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
* Kelas [IChartCategoryCollection](../../ichartcategorycollection/)
* Kelas [IChartData](../)
* Ruang nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)