---
title: get_Format()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει τις ιδιότητες διαμόρφωσης του επιπέδου σημείου δεδομένων. Διαβάστε IFormat.
type: docs
weight: 1
url: /el/aspose.slides.charts/ichartdatapointlevel/get_format/
---
## IChartDataPointLevel::get_Format() μέθοδος


Αντιπροσωπεύει τις ιδιότητες μορφοποίησης του επιπέδου σημείου δεδομένων. Διαβάστε [IFormat](../../iformat/).

```cpp
virtual System::SharedPtr<IFormat> Aspose::Slides::Charts::IChartDataPointLevel::get_Format()=0
```

## Σχόλια






```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Treemap, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);

auto dataPointLevel = series->get_DataPoints()->idx_get(7)->get_DataPointLevels()->idx_get(2);
dataPointLevel->get_Format()->get_Fill()->set_FillType(FillType::Solid);
dataPointLevel->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFormat](../../iformat/)
* Κλάση [IChartDataPointLevel](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)