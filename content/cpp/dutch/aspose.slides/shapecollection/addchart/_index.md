---
title: AddChart()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert een nieuw chart, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de shape collection.
type: docs
weight: 66
url: /nl/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) methode


Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de shape collection.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Het type diagram dat moet worden toegevoegd. |
| x | **float** | De x-coördinaat van het nieuwe diagram, in punten. |
| y | **float** | De y-coördinaat van het nieuwe diagram, in punten. |
| width | **float** | De breedte van het diagram, in punten. |
| height | **float** | De hoogte van het diagram, in punten. |

### Retourwaarde

Het nieuw aangemaakte [Charts::IChart](../../../aspose.slides.charts/ichart/).
## Opmerkingen



Het volgende voorbeeld laat zien hoe je een Chart maakt in PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantieert de Presentation-klasse die een PPTX-bestand vertegenwoordigt
auto pres = System::MakeObject<Presentation>();
// Toegang tot de eerste dia
auto slide = pres->get_Slides()->idx_get(0);
// Voegt een diagram toe met de standaardgegevens
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Stelt de titel van het diagram in
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Stelt in dat de eerste serie waarden toont
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Stelt de index in voor het diagramgegevensblad
int32_t defaultWorksheetIndex = 0;
// Haalt het werkblad met diagramgegevens op
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Verwijdert de standaard gegenereerde series en categorieën
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Voegt nieuwe series toe
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Voegt nieuwe categorieën toe
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Neemt de eerste diagramserie
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Vult de seriegegevens
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Stelt de vulkleur in voor de serie
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Neemt de tweede diagramserie
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Vult de seriegegevens
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Stelt de vulkleur in voor de serie
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Stelt het eerste label in om de categorienaam te tonen
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Stelt de serie in om de waarde voor het derde label te tonen
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Slaat het PPTX-bestand op naar schijf
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) methode


Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de shape collection.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Het type diagram dat moet worden toegevoegd. |
| x | **float** | De x-coördinaat van het nieuwe diagram, in punten. |
| y | **float** | De y-coördinaat van het nieuwe diagram, in punten. |
| width | **float** | De breedte van het diagram, in punten. |
| height | **float** | De hoogte van het diagram, in punten. |
| initWithSample | **bool** | Waarnaar `true` om het nieuwe diagram te initialiseren met voorbeeldreeksgegevens en instellingen; `false` om het diagram te maken zonder reeksen en alleen minimale instellingen, waardoor de creatie sneller gaat. |

### Retourwaarde

Het nieuw aangemaakte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Zie ook

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)