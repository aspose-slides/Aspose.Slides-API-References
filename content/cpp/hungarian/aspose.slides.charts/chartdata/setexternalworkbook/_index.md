---
title: SetExternalWorkbook()
second_title: Aspose.Slides C++ API referenciája
description: Beállítja a külső munkafüzetet adatforrásként a diagramhoz. A diagram adatai a cél munkafüzetből lesznek frissítve.
type: docs
weight: 183
url: /hu/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) method


Beállítja a külső munkafüzetet adatforrásként a diagramhoz. [Chart](../../chart/) adatok frissülnek a cél munkafüzetből.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Az elérési út a cél munkafüzethez |
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) method


Beállítja a külső munkafüzetet adatforrásként a diagramhoz.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Az elérési út a cél munkafüzethez |
| updateChartData | **bool** | Ha az érték hamis, csak a munkafüzet útvonala frissül. [Chart](../../chart/) adat nem lesz betöltve és frissítve a cél munkafüzetből. Akkor használható, amikor a cél munkafüzet nem létezik vagy nem érhető el. Ha az érték igaz, a diagram adatai frissülnek a cél munkafüzetből. |
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ChartData](../)
* Névtere [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)