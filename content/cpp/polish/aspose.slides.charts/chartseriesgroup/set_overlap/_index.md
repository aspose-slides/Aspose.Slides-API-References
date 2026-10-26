---
title: set_Overlap()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Określa, o ile słupki i kolumny mają zachodzić na siebie na wykresach 2-D, wyrażone jako procent (od -100% do 100%).
type: docs
weight: 170
url: /pl/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) metoda


Określa, o ile słupki i kolumny mają zachodzić na siebie na wykresach 2-D, wyrażone jako procent (od -100% do 100%).

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## Uwagi


* -100%: Maksymalne odstępy (słupki są całkowicie oddzielone).
* 0%: Słupki są rozmieszczone obok siebie bez nakładania się ani odstępów.
* 100%: Maksymalne nakładanie się (słupki całkowicie na siebie nachodzą). To własność odczyt/zapis **int8_t**.



Poniższy przykład pokazuje, jak ustawić nakładanie dla grupy serii wykresu i wyrenderować wynikowy wykres na formularzu: 
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