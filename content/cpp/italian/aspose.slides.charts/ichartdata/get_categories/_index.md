---
title: get_Categories()
second_title: Riferimento API di Aspose.Slides per C++
description: "Recupera le categorie primarie (o sia le categorie primarie che secondarie se IChartData::set_UseSecondaryCategories è impostato a false). Di sola lettura IChartCategoryCollection."
type: docs
weight: 40
url: /it/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() metodo

Recupera le categorie primarie (o sia le categorie primarie che secondarie se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato a false). Di sola lettura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## Osservazioni

Se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato a false, allora [IChartData::get_SecondaryCategories](../get_secondarycategories/) restituisce null e i dati in [IChartData::get_Categories](./) vengono usati sia per le serie primarie che per quelle secondarie. Se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato a true, i dati in [IChartData::get_SecondaryCategories](../get_secondarycategories/) vengono usati per le serie secondarie e i dati in [IChartData::get_Categories](./) vengono usati per le serie primarie. 

Esempio. Quali categorie sono associate alle serie - ChartData.Categories o ChartData.SecondaryCategories? 
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

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategoryCollection](../../ichartcategorycollection/)
* Classe [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)