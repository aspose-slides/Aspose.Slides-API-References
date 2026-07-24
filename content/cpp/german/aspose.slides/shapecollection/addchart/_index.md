---
title: AddChart()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formensammlung hinzu.
type: docs
weight: 66
url: /de/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) Methode

Erstellt ein neues Diagramm, initialisiert es mit Beispielseriendaten und -einstellungen und fügt es am Ende der Formensammlung hinzu.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Der Typ des hinzuzufügenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | **float** | Die Breite des Diagramms in Punkten. |
| height | **float** | Die Höhe des Diagramms in Punkten. |

### Rückgabewert

Das neu erstellte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Bemerkungen

Das folgende Beispiel zeigt, wie man ein Chart in PowerPoint [Presentation](../../presentation/) erstellt.
```cpp
// Instanziiert die Presentation-Klasse, die eine PPTX-Datei darstellt
auto pres = System::MakeObject<Presentation>();
// Greift auf die erste Folie zu
auto slide = pres->get_Slides()->idx_get(0);
// Fügt ein Diagramm mit den Standarddaten hinzu
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Setzt den Diagrammtitel
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Setzt die erste Serie, um Werte anzuzeigen
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Setzt den Index für das Diagrammdatenblatt
int32_t defaultWorksheetIndex = 0;
// Lädt das Diagrammdaten-Arbeitsblatt
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Löscht die standardmäßig erzeugten Serien und Kategorien
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Fügt neue Serien hinzu
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Fügt neue Kategorien hinzu
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Nimmt die erste Diagrammserie
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Füllt die Seriendaten
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Setzt die Füllfarbe für die Serie
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Nimmt die zweite Diagrammserie
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Füllt die Seriendaten
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Setzt die Füllfarbe für die Serie
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Setzt das erste Datenfeld, um den Kategorienamen anzuzeigen
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Setzt die Serie, um den Wert für das dritte Datenfeld anzuzeigen
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Speichert die PPTX-Datei auf dem Datenträger
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) Methode

Erstellt ein neues Diagramm, initialisiert es mit Beispielseriendaten und -einstellungen und fügt es am Ende der Formensammlung hinzu.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Der Typ des hinzuzufügenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | **float** | Die Breite des Diagramms in Punkten. |
| height | **float** | Die Höhe des Diagramms in Punkten. |
| initWithSample | **bool** | True, um das neue Diagramm mit Beispielseriendaten und -einstellungen zu initialisieren; false, um das Diagramm ohne Serien und nur mit minimalen Einstellungen zu erstellen, wodurch die Erstellung schneller erfolgt. |

### Rückgabewert

Das neu erstellte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Siehe auch

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)