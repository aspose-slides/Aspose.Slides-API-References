---
title: SetExternalWorkbook()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in extern arbetsbok som datakälla för diagrammet. Diagramdata kommer att uppdateras från målarbetsboken.
type: docs
weight: 196
url: /sv/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) metod


Ställer in extern arbetsbok som datakälla för diagrammet. [Chart](../../chart/) data kommer att uppdateras från målarbetsboken.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Sökväg till målarbetsboken |
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) metod


Ställer in extern arbetsbok som datakälla för diagrammet.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Sökväg till målarbetsboken |
| updateChartData | **bool** | Om värdet är falskt uppdateras endast arbetsboksökvägen. [Chart](../../chart/) data kommer inte att laddas och uppdateras från målarbetsboken. Kan användas när målarbetsboken inte finns eller inte är tillgänglig. Om värdet är sant uppdateras diagramdata från målarbetsboken. |
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Se även

* Klass [String](../../../system/string/)
* Klass [IChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)