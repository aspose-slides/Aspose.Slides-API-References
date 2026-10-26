---
title: get_UseSecondaryCategories()
second_title: Riferimento API di Aspose.Slides per C++
description: "Se impostato su false, allora ChartData::get_SecondaryCategories restituisce null e i dati in ChartData::get_Categories sono usati sia per le serie primarie che per le serie secondarie. Se impostato su true, allora i dati in ChartData::get_SecondaryCategories sono usati per le serie secondarie e i dati in ChartData::get_Categories sono usati per le serie primarie. Leggi bool."
type: docs
weight: 53
url: /it/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() metodo


Se impostato su false allora [ChartData::get_SecondaryCategories](../get_secondarycategories/) restituisce null e i dati in [ChartData::get_Categories](../get_categories/) sono usati sia per le serie primarie che per le serie secondarie. Se impostato su true allora i dati in [ChartData::get_SecondaryCategories](../get_secondarycategories/) sono usati per le serie secondarie e i dati in [ChartData::get_Categories](../get_categories/) sono usati per le serie primarie. Leggi **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## Osservazioni


Esempio. Quali categorie sono correlate alle serie - [ChartData::get_Categories](../get_categories/) o [ChartData::get_SecondaryCategories](../get_secondarycategories/)? 
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

* Classe [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)