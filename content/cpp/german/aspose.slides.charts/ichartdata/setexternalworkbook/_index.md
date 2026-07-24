---
title: SetExternalWorkbook()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die externe Arbeitsmappe als Datenquelle für das Diagramm fest. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert.
type: docs
weight: 196
url: /de/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) Methode

Legt die externe Arbeitsmappe als Datenquelle für das Diagramm fest. [Chart](../../chart/) Daten werden aus der Zielarbeitsmappe aktualisiert.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Pfad zur Zielarbeitsmappe |
## Bemerkungen

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) Methode

Legt die externe Arbeitsmappe als Datenquelle für das Diagramm fest.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Pfad zur Zielarbeitsmappe |
| updateChartData | **bool** | Wenn der Wert false ist, wird nur der Pfad zur Arbeitsmappe aktualisiert. [Chart](../../chart/) Daten werden nicht aus der Zielarbeitsmappe geladen und aktualisiert. Kann verwendet werden, wenn die Zielarbeitsmappe nicht existiert oder nicht verfügbar ist. Wenn der Wert true ist, werden die Diagrammdaten aus der Zielarbeitsmappe aktualisiert. |
## Bemerkungen

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IChartData](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)