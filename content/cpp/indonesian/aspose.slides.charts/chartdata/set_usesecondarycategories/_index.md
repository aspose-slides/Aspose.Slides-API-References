---
title: set_UseSecondaryCategories()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jika diatur ke false maka ChartData::get_SecondaryCategories mengembalikan null dan data di ChartData::get_Categories digunakan baik untuk seri utama maupun sekunder. Jika diatur ke true maka data di ChartData::get_SecondaryCategories digunakan untuk seri sekunder dan data di ChartData::get_Categories digunakan untuk seri utama. Tulis bool."
type: docs
weight: 66
url: /id/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) metode

Jika diatur ke false maka [ChartData::get_SecondaryCategories](../get_secondarycategories/) mengembalikan null dan data di [ChartData::get_Categories](../get_categories/) digunakan baik untuk seri utama maupun sekunder. Jika diatur ke true maka data di [ChartData::get_SecondaryCategories](../get_secondarycategories/) digunakan untuk seri sekunder dan data di [ChartData::get_Categories](../get_categories/) digunakan untuk seri utama. Tulis **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
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
* Pustaka [Aspose.Slides](../../../)