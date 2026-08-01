---
title: SetExternalWorkbook()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een extern werkboek in als gegevensbron voor de grafiek. Grafiekgegevens worden bijgewerkt vanuit het doelwerkboek.
type: docs
weight: 183
url: /nl/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) methode

Stelt een extern werkboek in als gegevensbron voor de grafiek. [Chart](../../chart/) gegevens worden bijgewerkt vanuit het doelwerkboek.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Pad naar het doelwerkboek |
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) methode

Stelt een extern werkboek in als gegevensbron voor de grafiek.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Pad naar het doelwerkboek |
| updateChartData | **bool** | Als de waarde false is, wordt alleen het pad van het werkboek bijgewerkt. [Chart](../../chart/) gegevens worden niet geladen en bijgewerkt vanuit het doelwerkboek. Kan worden gebruikt wanneer het doelwerkboek niet bestaat of niet beschikbaar is. Als de waarde true is, worden grafiekgegevens bijgewerkt vanuit het doelwerkboek. |
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [ChartData](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)