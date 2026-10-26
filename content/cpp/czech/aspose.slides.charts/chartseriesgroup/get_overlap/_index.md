---
title: get_Overlap()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100% do 100%).
type: docs
weight: 157
url: /cs/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() metoda


Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100% do 100%).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Poznámky


* -100%: Maximální rozestup (pruhy jsou zcela odděleny).
* 0%: Pruhy jsou umístěny vedle sebe bez překrytí nebo mezery.
* 100%: Maximální překrytí (pruhy se zcela překrývají). Tato vlastnost je čtení/zápis **int8_t**.



Následující příklad ukazuje, jak nastavit překrytí pro skupinu řady grafu a vykreslit výsledný graf na formuláři: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Nastavit překrytí na 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## Viz také

* Třída [ChartSeriesGroup](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)