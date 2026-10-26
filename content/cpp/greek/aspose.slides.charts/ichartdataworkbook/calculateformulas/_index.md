---
title: CalculateFormulas()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Υπολογίζει όλους τους τύπους στο βιβλίο εργασίας και ενημερώνει τις αντίστοιχες τιμές των κελιών.
type: docs
weight: 14
url: /el/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() μέθοδος


Υπολογίζει όλους τους τύπους στο βιβλίο εργασίας και ενημερώνει τις αντίστοιχες τιμές των κελιών.

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## Σχόλια



Το παράδειγμα δείχνει πώς να αντιστοιχίσετε έναν τύπο στο κελί και να υπολογίσετε μια τιμή. Η τιμή του \"B4\" κελιού ορίζεται σε 5. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## Δείτε επίσης

* Κλάση [IChartDataWorkbook](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)