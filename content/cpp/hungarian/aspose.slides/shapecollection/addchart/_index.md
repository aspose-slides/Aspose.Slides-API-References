---
title: AddChart()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy új diagramot, mintasorozat-adatokkal és beállításokkal inicializálja, és a formagyűjtemény végéhez adja hozzá.
type: docs
weight: 66
url: /hu/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metódus


Létrehoz egy új diagramot, mintasorozat-adatokkal és beállításokkal inicializálja, majd a formagyűjtemény végéhez adja hozzá.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | A hozzáadandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontban. |
| y | **float** | Az új diagram y-koordinátája pontban. |
| width | **float** | A diagram szélessége pontban. |
| height | **float** | A diagram magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Megjegyzés



A következő példa bemutatja, hogyan hozható létre Chart a PowerPointban [Presentation](../../presentation/). 
```cpp
// Példányosítja a Presentation osztályt, amely egy PPTX fájlt képvisel
auto pres = System::MakeObject<Presentation>();
// Eléri az első diát
auto slide = pres->get_Slides()->idx_get(0);
// Diagramot ad hozzá az alapértelmezett adataival
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Beállítja a diagram címét
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Beállítja, hogy az első sorozat értékeket jelenítsen meg
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Beállítja a diagram adatlap indexét
int32_t defaultWorksheetIndex = 0;
// Lekéri a diagram adatlapját
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Törli az alapértelmezés szerint generált sorozatokat és kategóriákat
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Új sorozatot ad hozzá
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Új kategóriákat ad hozzá
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Az első diagram sorozatot veszi
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Feltölti a sorozat adatait
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Beállítja a sorozat kitöltőszínét
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// A második diagram sorozatot veszi
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Feltölti a sorozat adatait
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Beállítja a sorozat kitöltőszínét
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Beállítja, hogy az első címke megjelenítse a kategória nevét
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Beállítja, hogy a sorozat megjelenítse az értéket a harmadik címkéhez
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Mentse a PPTX fájlt a lemezre
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metódus


Létrehoz egy új diagramot, mintasorozat-adatokkal és beállításokkal inicializálja, majd a formagyűjtemény végéhez adja hozzá.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | A hozzáadandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontban. |
| y | **float** | Az új diagram y-koordinátája pontban. |
| width | **float** | A diagram szélessége pontban. |
| height | **float** | A diagram magassága pontban. |
| initWithSample | **bool** | Igaz, ha a új diagramot mintasorozat-adatokkal és beállításokkal kell inicializálni; hamis, ha a diagramot sorozatok nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb létrehozást eredményez. |

### Visszatérési érték

Az újonnan létrehozott [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Lásd még

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)