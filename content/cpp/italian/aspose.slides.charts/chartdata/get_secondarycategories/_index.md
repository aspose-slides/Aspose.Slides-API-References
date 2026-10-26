---
title: get_SecondaryCategories()
second_title: Riferimento API di Aspose.Slides per C++
description: "Ottiene le categorie secondarie se ChartData::get_UseSecondaryCategories è vero. Sola lettura IChartCategoryCollection."
type: docs
weight: 79
url: /it/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() metodo

Ottiene le categorie secondarie se [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) è vero. Sola lettura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## Osservazioni

Se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato su false allora [ChartData::get_SecondaryCategories](./) restituisce null e i dati in [ChartData::get_Categories](../get_categories/) sono usati sia per le serie primarie che secondarie. Se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato su true allora i dati in [ChartData::get_SecondaryCategories](./) sono usati per le serie secondarie e i dati in [ChartData::get_Categories](../get_categories/) sono usati per le serie primarie. 

Esempio. Quali categorie sono legate alle serie - [ChartData::get_Categories](../get_categories/) o [ChartData::get_SecondaryCategories](./)? 
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
* Classe [ChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)