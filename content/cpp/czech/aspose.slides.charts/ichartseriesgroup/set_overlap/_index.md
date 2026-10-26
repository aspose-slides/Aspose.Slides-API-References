---
title: set_Overlap()
second_title: Aspose.Slides pro C++ - referenční příručka
description: Určuje, o kolik se mají pruhy a sloupce překrývat v 2-D diagramech, jako procento (od -100% do 100%).
type: docs
weight: 196
url: /cs/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) metoda


Určuje, o kolik se mají pruhy a sloupce překrývat v 2-D diagramech, jako procento (od -100% do 100%).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Poznámky


* -100%: Maximální rozestup (pruhy jsou zcela oddělené).
* 0%: Pruhy jsou umístěny vedle sebe bez překrytí nebo mezery.
* 100%: Maximální překrytí (pruhy se zcela překrývají). Tato vlastnost je čtení/zápis **int8_t**.



Následující příklad ukazuje, jak nastavit překrytí pro skupinu řad grafu a vykreslit vzniklý graf ve formuláři: 
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

* Třída [IChartSeriesGroup](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)