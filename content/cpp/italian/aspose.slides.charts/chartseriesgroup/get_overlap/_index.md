---
title: get_Overlap()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%).
type: docs
weight: 157
url: /it/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() metodo

Specifica quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Osservazioni

* -100%: Spaziatura massima (le barre sono completamente separate).
* 0%: Le barre sono collocate una accanto all'altra senza sovrapposizione o spaziatura.
* 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è lettura/scrittura **int8_t**.

Il seguente esempio dimostra come impostare la sovrapposizione per un gruppo di serie di grafico e visualizzare il grafico risultante su un modulo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Imposta la sovrapposizione al 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Vedi anche

* Classe [ChartSeriesGroup](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)