---
title: set_UseSecondaryCategories()
second_title: Riferimento API di Aspose.Slides per C++
description: "Se impostato su false allora ChartData::get_SecondaryCategories restituisce null e i dati in ChartData::get_Categories sono usati sia per le serie primarie che per le secondarie. Se impostato su true allora i dati in ChartData::get_SecondaryCategories sono usati per le serie secondarie e i dati in ChartData::get_Categories sono usati per le serie primarie. Scrivi bool."
type: docs
weight: 66
url: /it/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) metodo

Se impostato su false allora [ChartData::get_SecondaryCategories](../get_secondarycategories/) restituisce null e i dati in [ChartData::get_Categories](../get_categories/) vengono usati sia per le serie primarie che per le secondarie. Se impostato su true allora i dati in [ChartData::get_SecondaryCategories](../get_secondarycategories/) vengono usati per le serie secondarie e i dati in [ChartData::get_Categories](../get_categories/) vengono usati per le serie primarie. Scrivi **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
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
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)