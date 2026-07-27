---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides for C++ Referência da API
description: Representa o formato das linhas de guia dos rótulos de dados. Somente leitura IChartLinesFormat.
type: docs
weight: 14
url: /pt/aspose.slides.charts/idatalabelcollection/get_leaderlinesformat/
---
## IDataLabelCollection::get_LeaderLinesFormat() método


Representa o formato das linhas de guia dos rótulos de dados. Somente leitura [IChartLinesFormat](../../ichartlinesformat/).

```cpp
virtual System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::IDataLabelCollection::get_LeaderLinesFormat()=0
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartLinesFormat](../../ichartlinesformat/)
* Classe [IDataLabelCollection](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)