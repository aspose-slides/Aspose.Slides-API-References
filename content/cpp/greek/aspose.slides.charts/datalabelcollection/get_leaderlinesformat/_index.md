---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει τη μορφή γραμμών οδηγού ετικετών δεδομένων. Μόνο για ανάγνωση IChartLinesFormat.
type: docs
weight: 66
url: /el/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() μέθοδος

Αντιπροσωπεύει τη μορφή γραμμών οδηγού ετικετών δεδομένων. Μόνο για ανάγνωση [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartLinesFormat](../../ichartlinesformat/)
* Κλάση [DataLabelCollection](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)