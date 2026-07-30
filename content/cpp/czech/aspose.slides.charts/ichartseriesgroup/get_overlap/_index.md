---
title: get_Overlap()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje, jak moc mají pruhy a sloupce překrývat na 2-D grafech, jako procento (od -100% do 100%).
type: docs
weight: 183
url: /cs/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() method


Určuje, jak moc mají pruhy a sloupce překrývat na 2-D grafech, jako procento (od -100% do 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## Poznámky


* -100%: Maximální rozestup (pruhy jsou zcela odděleny).
* 0%: Pruhy jsou umístěny vedle sebe bez překrytí nebo rozestupu.
* 100%: Maximální překrytí (pruhy se navzájem zcela překrývají). Tato vlastnost je čtení/zápis **int8_t**.



Následující příklad ukazuje, jak nastavit překrytí pro skupinu řady grafu a vykreslit výsledný graf na formuláři: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Nastavte překrytí na 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## Viz také

* Třída [IChartSeriesGroup](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)