---
title: set_UseSecondaryCategories()
second_title: Riferimento API di Aspose.Slides per C++
description: "Se impostato a false allora IChartData::get_SecondaryCategories restituisce null e i dati in IChartData::get_Categories vengono utilizzati sia per le serie primarie che per quelle secondarie. Se impostato a true allora i dati in IChartData::get_SecondaryCategories vengono utilizzati per le serie secondarie e i dati in IChartData::get_Categories vengono utilizzati per le serie primarie. Scrivi bool."
type: docs
weight: 66
url: /it/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) metodo


Se impostato a false allora [IChartData::get_SecondaryCategories](../get_secondarycategories/) restituisce null e i dati in [IChartData::get_Categories](../get_categories/) vengono utilizzati sia per le serie primarie che per quelle secondarie. Se impostato a true allora i dati in [IChartData::get_SecondaryCategories](../get_secondarycategories/) vengono utilizzati per le serie secondarie e i dati in [IChartData::get_Categories](../get_categories/) vengono utilizzati per le serie primarie. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## Osservazioni


Esempio. Quali categorie sono associate alle serie - ChartData.Categories o ChartData.SecondaryCategories? 
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

* Classe [IChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)