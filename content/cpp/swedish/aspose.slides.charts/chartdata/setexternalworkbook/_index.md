---
title: SetExternalWorkbook()
second_title: Aspose.Slides för C++ API-referens
description: Anger extern arbetsbok som datakälla för diagrammet. Diagramdata kommer att uppdateras från målarboken.
type: docs
weight: 183
url: /sv/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) metod

Anger den externa arbetsboken som datakälla för diagrammet. [Chart](../../chart/) data kommer att uppdateras från målarbetsboken.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Sökväg till målarboken |

## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) metod

Anger den externa arbetsboken som datakälla för diagrammet.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Sökväg till målarboken |
| updateChartData | **bool** | Om värdet är falskt uppdateras endast arbetsbokssökvägen. [Chart](../../chart/) data kommer inte att läsas in och uppdateras från målarboken. Kan användas när målarboken inte finns eller inte är tillgänglig. Om värdet är sant uppdateras diagramdata från målarboken. |

## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Se även

* Klass [String](../../../system/string/)
* Klass [ChartData](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)