---
title: GetRange()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a diagram adat tartományát.
type: docs
weight: 170
url: /hu/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() metódus

Lekéri a diagram adat tartományát.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```

### Visszatérési érték

Cellák adat-tartomány képlete. Például: "Sheet1!$A$1:$C$4"
## Megjegyzés

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IChartData](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)