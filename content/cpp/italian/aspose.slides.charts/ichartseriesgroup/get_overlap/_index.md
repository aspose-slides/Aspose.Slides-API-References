---
title: get_Overlap()
second_title: Aspose.Slides per C++ Riferimento API
description: Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%).
type: docs
weight: 183
url: /it/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() metodo


Specifica di quanto le barre e le colonne devono sovrapporsi nei grafici 2-D, come percentuale (da -100% a 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## Osservazioni


* -100%: Spaziatura massima (le barre sono completamente separate).
* 0%: Le barre sono posizionate fianco a fianco senza sovrapposizione o spaziatura.
* 100%: Sovrapposizione massima (le barre si sovrappongono completamente). Questa proprietà è lettura/scrittura **int8_t**.



L'esempio seguente dimostra come impostare la sovrapposizione per un gruppo di serie del grafico e renderizzare il grafico risultante su un modulo: 
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

* Classe [IChartSeriesGroup](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)