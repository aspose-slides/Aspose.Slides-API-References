---
title: get_Categories()
second_title: Riferimento API di Aspose.Slides per C++
description: "Recupera le categorie primarie (o sia le categorie primarie che secondarie se ChartData::set_UseSecondaryCategories è impostato su false). Solo lettura IChartCategoryCollection."
type: docs
weight: 40
url: /it/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() metodo

Ottiene le categorie primarie (o sia le categorie primarie che secondarie se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato su false). Solo lettura [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## Osservazioni

Se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato su false, allora [ChartData::get_SecondaryCategories](../get_secondarycategories/) restituisce null e i dati in [ChartData::get_Categories](./) sono usati sia per le serie primarie che secondarie. Se [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) è impostato su true, allora i dati in [ChartData::get_SecondaryCategories](../get_secondarycategories/) sono usati per le serie secondarie e i dati in [ChartData::get_Categories](./) sono usati per le serie primarie. 

Esempio. Quali categorie sono correlate alla serie - [ChartData::get_Categories](./) o [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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
* Classe [ChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)