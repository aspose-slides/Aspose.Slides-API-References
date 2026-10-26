---
title: get_UseSecondaryCategories()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jika disetel ke false maka ChartData::get_SecondaryCategories mengembalikan null dan data di ChartData::get_Categories digunakan baik untuk seri utama maupun sekunder. Jika disetel ke true maka data di ChartData::get_SecondaryCategories digunakan untuk seri sekunder dan data di ChartData::get_Categories digunakan untuk seri utama. Baca bool."
type: docs
weight: 53
url: /id/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() metode


Jika disetel ke false maka [ChartData::get_SecondaryCategories](../get_secondarycategories/) mengembalikan null dan data di [ChartData::get_Categories](../get_categories/) digunakan baik untuk seri utama maupun sekunder. Jika disetel ke true maka data di [ChartData::get_SecondaryCategories](../get_secondarycategories/) digunakan untuk seri sekunder dan data di [ChartData::get_Categories](../get_categories/) digunakan untuk seri utama. Baca **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Catatan


Contoh. Kategori apa yang terkait dengan seri - [ChartData::get_Categories](../get_categories/) atau [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* Kelas [ChartData](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Perpustakaan [Aspose.Slides](../../../)