---
title: get_UseSecondaryCategories()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jika diatur ke false maka IChartData::get_SecondaryCategories mengembalikan null dan data dalam IChartData::get_Categories digunakan baik untuk seri utama maupun sekunder. Jika diatur ke true maka data dalam IChartData::get_SecondaryCategories digunakan untuk seri sekunder dan data dalam IChartData::get_Categories digunakan untuk seri utama. Baca bool."
type: docs
weight: 53
url: /id/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() metode

Jika diatur ke false maka [IChartData::get_SecondaryCategories](../get_secondarycategories/) mengembalikan null dan data dalam [IChartData::get_Categories](../get_categories/) digunakan baik untuk seri utama maupun sekunder. Jika diatur ke true maka data dalam [IChartData::get_SecondaryCategories](../get_secondarycategories/) digunakan untuk seri sekunder dan data dalam [IChartData::get_Categories](../get_categories/) digunakan untuk seri utama. Baca **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Catatan

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

* Kelas [IChartData](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Pustaka [Aspose.Slides](../../../)