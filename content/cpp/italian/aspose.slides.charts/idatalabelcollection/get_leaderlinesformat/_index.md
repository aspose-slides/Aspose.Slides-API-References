---
title: get_LeaderLinesFormat()
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta il formato delle linee guida delle etichette dati. Sola lettura IChartLinesFormat.
type: docs
weight: 14
url: /it/aspose.slides.charts/idatalabelcollection/get_leaderlinesformat/
---
## IDataLabelCollection::get_LeaderLinesFormat() metodo

Rappresenta il formato delle linee guida delle etichette dati. Sola lettura [IChartLinesFormat](../../ichartlinesformat/).

```cpp
virtual System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::IDataLabelCollection::get_LeaderLinesFormat()=0
```

## Osservazioni

Esempio:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartLinesFormat](../../ichartlinesformat/)
* Classe [IDataLabelCollection](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)