---
title: set_Overlap()
second_title: Aspose.Slides dla C++ API Reference
description: Określa, jak bardzo słupki i kolumny mają nachodzić na wykresach 2-D, wyrażone w procentach (od -100% do 100%).
type: docs
weight: 196
url: /pl/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) metoda

Określa, jak bardzo słupki i kolumny mają nachodzić na wykresach 2-D, wyrażone w procentach (od -100% do 100%).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Uwagi

* -100%: Maksymalne odstępy (słupki są całkowicie oddzielone).
* 0%: Słupki są umieszczone obok siebie bez nachodzenia ani odstępów.
* 100%: Maksymalne nachodzenie (słupki całkowicie nachodzą na siebie). Ta właściwość jest odczyt/zapis **int8_t**.

Poniższy przykład pokazuje, jak ustawić nachodzenie dla grupy serii wykresu i wyrenderować powstały wykres na formularzu:
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