---
title: get_Overlap()
second_title: Aspose.Slides dla C++ Referencja API
description: Określa, jak bardzo słupki i kolumny mają nachodzić na wykresach 2-D, jako procent (od -100% do 100%).
type: docs
weight: 183
url: /pl/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() method

Określa, jak bardzo słupki i kolumny mają nachodzić na wykresach 2-D, jako procent (od -100% do 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## Uwagi

* -100%: Maksymalne rozmieszczenie (słupki są całkowicie oddzielone).
* 0%: Słupki są ustawione obok siebie bez nachodzenia ani odstępu.
* 100%: Maksymalne nachodzenie (słupki całkowicie nachodzą na siebie). Ta właściwość jest odczyt/zapis **int8_t**.

Poniższy przykład pokazuje, jak ustawić nachodzenie dla grupy serii wykresu i wyrenderować powstały wykres w formularzu: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Ustaw nachodzenie na 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Zobacz także

* Klasa [IChartSeriesGroup](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)