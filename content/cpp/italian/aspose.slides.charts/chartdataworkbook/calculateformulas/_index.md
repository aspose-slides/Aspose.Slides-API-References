---
title: CalculateFormulas()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola tutte le formule nella cartella di lavoro e aggiorna i valori delle celle corrispondenti.
type: docs
weight: 53
url: /it/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() metodo

Calcola tutte le formule nella cartella di lavoro e aggiorna i valori delle celle corrispondenti.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## Osservazioni

L'esempio mostra come assegnare una formula alla cella e calcolare un valore. Il valore della cella \"B4\" viene impostato a 5. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## Vedi anche

* Classe [ChartDataWorkbook](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)