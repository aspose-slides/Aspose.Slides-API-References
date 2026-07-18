---
title: GetRange()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει το εύρος δεδομένων του διαγράμματος.
type: docs
weight: 157
url: /el/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() μέθοδος


Λαμβάνει το εύρος δεδομένων του διαγράμματος.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Τιμή Επιστροφής

Τύπος εύρους δεδομένων κελιών. Π.χ: "Sheet1!$A$1:$C$4"
## Παρατηρήσεις




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [ChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)