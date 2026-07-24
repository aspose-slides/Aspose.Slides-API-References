---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API Referansı
description: "Eğer false olarak ayarlanırsa ChartData::get_SecondaryCategories null döndürür ve ChartData::get_Categories içindeki veri hem birincil hem de ikincil seriler için kullanılır. Eğer true olarak ayarlanırsa ChartData::get_SecondaryCategories içindeki veri ikincil seri için, ChartData::get_Categories içindeki veri birincil seri için kullanılır. Okur bool."
type: docs
weight: 53
url: /tr/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() metot


false olarak ayarlanırsa [ChartData::get_SecondaryCategories](../get_secondarycategories/) null döndürür ve [ChartData::get_Categories](../get_categories/) içindeki veri birincil ve ikincil seriler için kullanılır. true olarak ayarlanırsa [ChartData::get_SecondaryCategories](../get_secondarycategories/) içindeki veri ikincil seri için, [ChartData::get_Categories](../get_categories/) içindeki veri birincil seri için kullanılır. Okur **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Açıklamalar


Örnek. Hangi kategoriler serilere ilişkilidir - [ChartData::get_Categories](../get_categories/) veya [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // ilgili kategoriler series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // ilgili kategoriler series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Bkz

* Sınıf [ChartData](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)