---
title: get_SecondaryCategories()
second_title: Riferimento API Aspose.Slides per C++
description: "Ottiene le categorie secondarie se IChartData::get_UseSecondaryCategories è true. Solo lettura IChartCategoryCollection."
type: docs
weight: 79
url: /it/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() metodo

Ottiene le categorie secondarie se [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) è vero. Solo lettura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## Osservazioni

Se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato su false allora [IChartData::get_SecondaryCategories](./) restituisce null e i dati in [IChartData::get_Categories](../get_categories/) sono usati sia per le serie primarie che per le secondarie. Se [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato su true allora i dati in [IChartData::get_SecondaryCategories](./) sono usati per le serie secondarie e i dati in [IChartData::get_Categories](../get_categories/) sono usati per le serie primarie.

Esempio. Quali categorie sono correlate alle serie - ChartData.Categories o ChartData.SecondaryCategories?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // le categorie correlate sono series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // le categorie correlate sono series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategoryCollection](../../ichartcategorycollection/)
* Classe [IChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)