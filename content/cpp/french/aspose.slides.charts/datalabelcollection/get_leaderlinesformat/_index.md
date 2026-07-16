---
title: get_LeaderLinesFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le format des lignes directrices des étiquettes de données. Lecture seule IChartLinesFormat.
type: docs
weight: 66
url: /fr/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() method


Représente le format des lignes directrices des étiquettes de données. Lecture seule [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
```

## Remarques


Exemple :
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartLinesFormat](../../ichartlinesformat/)
* Classe [DataLabelCollection](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)