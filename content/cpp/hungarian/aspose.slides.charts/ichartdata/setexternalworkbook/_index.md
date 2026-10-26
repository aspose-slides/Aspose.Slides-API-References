---
title: SetExternalWorkbook()
second_title: Aspose.Slides C++ API referenciája
description: Beállítja a külső munkafüzetet adatforrásként a diagramhoz. A diagram adatai frissítve lesznek a cél munkafüzettől.
type: docs
weight: 196
url: /hu/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) metódus


Beállítja a külső munkafüzetet a diagram adatforrásaként. [Chart](../../chart/) adatok frissítve lesznek a cél munkafüzettől.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Útvonal a cél munkafüzethez |
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) metódus


Beállítja a külső munkafüzetet a diagram adatforrásaként.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Útvonal a cél munkafüzethez |
| updateChartData | **bool** | Ha az érték hamis, csak a munkafüzet útvonala lesz frissítve. [Chart](../../chart/) adatok nem lesznek betöltve és frissítve a cél munkafüzettől. Használható, ha a cél munkafüzet nem létezik vagy nem érhető el. Ha az érték igaz, a diagram adatok frissülnek a cél munkafüzettől. |
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IChartData](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)