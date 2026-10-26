---
title: get_UseSecondaryCategories()
second_title: Riferimento API di Aspose.Slides per C++
description: "Se impostato su false allora IChartData::get_SecondaryCategories restituisce null e i dati in IChartData::get_Categories sono usati sia per le serie primarie che secondarie. Se impostato su true allora i dati in IChartData::get_SecondaryCategories sono usati per le serie secondarie e i dati in IChartData::get_Categories sono usati per le serie primarie. Leggi bool."
type: docs
weight: 53
url: /it/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() metodo

Se impostato su false, allora [IChartData::get_SecondaryCategories](../get_secondarycategories/) restituisce null e i dati in [IChartData::get_Categories](../get_categories/) sono usati sia per le serie primarie che secondarie. Se impostato su true, allora i dati in [IChartData::get_SecondaryCategories](../get_secondarycategories/) sono usati per le serie secondarie e i dati in [IChartData::get_Categories](../get_categories/) sono usati per le serie primarie. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## Osservazioni

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

* Classe [IChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)