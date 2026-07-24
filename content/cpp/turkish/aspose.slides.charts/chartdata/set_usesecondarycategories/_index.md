---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides for C++ API Referansı
description: "Eğer false olarak ayarlanırsa ChartData::get_SecondaryCategories null döndürür ve ChartData::get_Categories içindeki veriler birincil ve ikincil seriler için her ikisinde de kullanılır. Eğer true olarak ayarlanırsa ChartData::get_SecondaryCategories içindeki veriler ikincil seri için, ChartData::get_Categories içindeki veriler birincil seri için kullanılır. bool yazın."
type: docs
weight: 66
url: /tr/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) yöntemi

false olarak ayarlandığında [ChartData::get_SecondaryCategories](../get_secondarycategories/) null döndürür ve [ChartData::get_Categories](../get_categories/) içindeki veri birincil ve ikincil seriler için her iki durumda da kullanılır. true olarak ayarlandığında [ChartData::get_SecondaryCategories](../get_secondarycategories/) içindeki veri ikincil seri için, [ChartData::get_Categories](../get_categories/) içindeki veri birincil seri için kullanılır. **bool** yazın.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
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

## İlgili

* Sınıf [ChartData](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)