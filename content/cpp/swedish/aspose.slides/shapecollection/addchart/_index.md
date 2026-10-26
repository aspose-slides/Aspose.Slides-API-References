---
title: AddChart()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av shape collection.
type: docs
weight: 66
url: /sv/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metod


Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av shape collection.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typen av diagram som ska läggas till. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på diagrammet, i punkter. |
| height | **float** | Höjden på diagrammet, i punkter. |

### Returvärde

Det nyss skapade [Charts::IChart](../../../aspose.slides.charts/ichart/).
## Anmärkningar



Följande exempel visar hur man skapar Chart i PowerPoint [Presentation](../../presentation/). 
```cpp
// Skapar en instans av Presentation-klassen som representerar en PPTX-fil
auto pres = System::MakeObject<Presentation>();
// Hämtar den första bilden
auto slide = pres->get_Slides()->idx_get(0);
// Lägger till ett diagram med standarddata
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Sätter diagramtitel
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Ställer in att den första serien ska visa värden
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Ställer in indexet för diagramdatabladet
int32_t defaultWorksheetIndex = 0;
// Hämtar diagramdatabladet
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Tar bort de automatiskt genererade serierna och kategorierna
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Lägger till nya serier
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Lägger till nya kategorier
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Tar den första diagramserien
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Fyller seriedata
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Anger fyllningsfärgen för serien
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Tar den andra diagramserien
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Fyller seriedata
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Anger fyllningsfärgen för serien
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Ställer in att den första etiketten ska visa kategorinamn
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Ställer in att serien ska visa värdet för den tredje etiketten
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Sparar PPTX-filen till disk
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metod


Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av shape collection.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typen av diagram som ska läggas till. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på diagrammet, i punkter. |
| height | **float** | Höjden på diagrammet, i punkter. |
| initWithSample | **bool** | true för att initiera det nya diagrammet med exempelseriedata och inställningar; false för att skapa diagrammet utan serier och endast minimala inställningar, vilket gör skapandet snabbare. |

### Returvärde

Det nyss skapade [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Se också

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)