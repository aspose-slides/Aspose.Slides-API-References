---
title: get_Overlap()
second_title: Aspose.Slides dla C++ – Referencja API
description: Określa, jak bardzo słupki i kolumny mają się nakładać na wykresach 2-D, wyrażone jako procent (od -100% do 100%).
type: docs
weight: 157
url: /pl/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() metoda

Określa, jak bardzo słupki i kolumny mają się na siebie nakładać na wykresach 2-D, wyrażone jako procent (od -100% do 100%).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Uwagi

* -100%: maksymalne odstępy (słupki są całkowicie oddzielone).
* 0%: słupki są ułożone obok siebie bez nakładania się ani odstępu.
* 100%: maksymalne nakładanie się (słupki całkowicie na siebie nachodzą). Ta właściwość jest odczyt/zapis **int8_t**.

Poniższy przykład pokazuje, jak ustawić nakładanie dla grupy serii wykresu i wyrenderować powstały wykres w formularzu:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Ustaw nakładanie na 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Zobacz także

* Klasa [ChartSeriesGroup](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)