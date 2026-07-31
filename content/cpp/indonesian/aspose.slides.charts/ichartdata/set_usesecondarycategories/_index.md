---
title: set_UseSecondaryCategories()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jika disetel ke false maka IChartData::get_SecondaryCategories mengembalikan null dan data dalam IChartData::get_Categories digunakan baik untuk seri utama maupun sekunder. Jika disetel ke true maka data dalam IChartData::get_SecondaryCategories digunakan untuk seri sekunder dan data dalam IChartData::get_Categories digunakan untuk seri utama. Tulis bool."
type: docs
weight: 66
url: /id/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) metode

Jika disetel ke false maka [IChartData::get_SecondaryCategories](../get_secondarycategories/) mengembalikan null dan data dalam [IChartData::get_Categories](../get_categories/) digunakan untuk seri utama dan sekunder. Jika disetel ke true maka data dalam [IChartData::get_SecondaryCategories](../get_secondarycategories/) digunakan untuk seri sekunder dan data dalam [IChartData::get_Categories](../get_categories/) digunakan untuk seri utama. Tulis **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
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
* Library [Aspose.Slides](../../../)