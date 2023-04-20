---
title: AddChart()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection.
type: docs
weight: 66
url: /cpp/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) method


Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |

### Return Value

Created chart.
## Remarks



The following example shows how to create Chart in PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantiates the Presentation class that represents a PPTX file
auto pres = System::MakeObject<Presentation>();
// Accesses the first slide
auto slide = pres->get_Slides()->idx_get(0);
// Adds a chart with its default data
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Sets the chart title
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Sets the first series to show values
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Sets the index for the chart data sheet
int32_t defaultWorksheetIndex = 0;
// Gets the chart data worksheet
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Deletes the default generated series and categories
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Adds new series
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Adds new categories
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Takes the first chart series
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Populates series data
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Sets the fill color for the series
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Takes the second chart series
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Populates series data
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Sets the fill color for series
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Sets the first label to show Category name
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Sets the series to show the value for the third label
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Saves the PPTX file to disk
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) method


Creates a new Chart and adds it to the end of the collection.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Type of chart. |
| x | **float** | X coordinate of a new chart. |
| y | **float** | Y coordinate of a new chart. |
| width | **float** | Chart's width. |
| height | **float** | Chart's height. |
| initWithSample | **bool** | If true then new chart will be initialized with sample series data and settings. If false then new chart will have no series and minimum settings. In this case chart creation will be more fast. |

### Return Value

Created chart.

## See Also

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)