---
title: GetRange()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a diagram adat tartományát.
type: docs
weight: 157
url: /hu/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() metódus


Lekéri a diagram adat tartományát.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Visszatérési érték

Cellák adat-tartomány képlete. Például: "Sheet1!$A$1:$C$4"
## Megjegyzések


```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ChartData](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)