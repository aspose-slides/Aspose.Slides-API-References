---
title: get_SecondaryCategories()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan kategori sekunder jika ChartData::get_UseSecondaryCategories bernilai true. Hanya baca IChartCategoryCollection."
type: docs
weight: 79
url: /id/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() metode


Mendapatkan kategori sekunder jika [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) adalah true. Hanya baca [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Catatan


Jika [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke false maka [ChartData::get_SecondaryCategories](./) mengembalikan null dan data di [ChartData::get_Categories](../get_categories/) digunakan baik untuk seri utama maupun sekunder. Jika [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) diatur ke true maka data di [ChartData::get_SecondaryCategories](./) digunakan untuk seri sekunder dan data di [ChartData::get_Categories](../get_categories/) digunakan untuk seri utama. 

Contoh. Kategori apa yang terkait dengan seri - [ChartData::get_Categories](../get_categories/) atau [ChartData::get_SecondaryCategories](./)? 
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
* Kelas [ChartData](../)
* Ruang nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)