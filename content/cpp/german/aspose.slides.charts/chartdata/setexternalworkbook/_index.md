---
title: SetExternalWorkbook()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert.
type: docs
weight: 183
url: /de/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) Methode

Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. [Chart](../../chart/) Daten werden aus der Zielarbeitsmappe aktualisiert.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Pfad zur Zielarbeitsmappe |
## Hinweise

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) Methode

Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Pfad zur Zielarbeitsmappe |
| updateChartData | **bool** | Wenn der Wert false ist, wird nur der Pfad zur Arbeitsmappe aktualisiert. [Chart](../../chart/) Daten werden nicht geladen und aus der Zielarbeitsmappe aktualisiert. Kann verwendet werden, wenn die Zielarbeitsmappe nicht existiert oder nicht verfügbar ist. Wenn der Wert true ist, werden die Diagrammdaten aus der Zielarbeitsmappe aktualisiert. |
## Hinweise

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [ChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)