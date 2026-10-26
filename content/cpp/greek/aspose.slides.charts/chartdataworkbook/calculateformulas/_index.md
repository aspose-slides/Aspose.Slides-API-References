---
title: CalculateFormulas()
second_title: Aspose.Slides για C++ API Αναφορά
description: Υπολογίζει όλους τους τύπους στο βιβλίο εργασίας και ενημερώνει τις αντίστοιχες τιμές των κελιών.
type: docs
weight: 53
url: /el/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() μέθοδος


Υπολογίζει όλους τους τύπους στο βιβλίο εργασίας και ενημερώνει τις αντίστοιχες τιμές των κελιών.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## Παρατηρήσεις



Το παράδειγμα δείχνει πώς να εκχωρήσετε έναν τύπο στο κελί και να υπολογίσετε μια τιμή. Η τιμή του κελιού \"B4\" ορίζεται σε 5. 
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

* Κλάση [ChartDataWorkbook](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)