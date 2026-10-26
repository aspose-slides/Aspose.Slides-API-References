---
title: AddChart()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a přidá jej na konec kolekce tvarů.
type: docs
weight: 66
url: /cs/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metoda

Vytvoří nový Chart, inicializuje jej ukázkovými daty řady a nastaveními a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | The type of chart to add. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the chart, in points. |
| height | **float** | The height of the chart, in points. |

### Návratová hodnota

Nově vytvořený [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Poznámky

Následující příklad ukazuje, jak vytvořit Chart v PowerPointu [Presentation](../../presentation/). 
```cpp
// Vytvoří instanci třídy Presentation, která představuje soubor PPTX
auto pres = System::MakeObject<Presentation>();
// Přistupuje k první snímku
auto slide = pres->get_Slides()->idx_get(0);
// Přidá graf s výchozími daty
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Nastaví název grafu
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Nastaví první řadu tak, aby zobrazovala hodnoty
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Nastaví index listu s daty grafu
int32_t defaultWorksheetIndex = 0;
// Získá list s daty grafu
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Odstraní výchozí generované řady a kategorie
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Přidá novou řadu
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
// Přidá novou řadu
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Přidá nové kategorie
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Získá první řadu grafu
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Naplní data řady
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Nastaví barvu výplně řady
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Získá druhou řadu grafu
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Naplní data řady
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Nastaví barvu výplně řady
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Nastaví první popisek tak, aby zobrazoval název kategorie
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Nastaví řadu, aby zobrazovala hodnotu pro třetí popisek
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Uloží soubor PPTX na disk
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metoda

Vytvoří nový Chart, inicializuje jej ukázkovými daty řady a nastaveními a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | The type of chart to add. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the chart, in points. |
| height | **float** | The height of the chart, in points. |
| initWithSample | **bool** | true pro inicializaci nového Chartu s ukázkovými daty řady a nastaveními; false pro vytvoření Chartu bez řad a pouze s minimálními nastaveními, což urychluje vytvoření. |

### Návratová hodnota

Nově vytvořený [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Viz také

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChart](../../../aspose.slides.charts/ichart/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)