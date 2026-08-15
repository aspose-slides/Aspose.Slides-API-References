---
title: AddChart()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個新的圖表，使用範例系列資料和設定進行初始化，並將其加入形狀集合的末端。
type: docs
weight: 66
url: /zh-hant/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) 方法

建立一個新的圖表，使用範例系列資料和設定進行初始化，然後將其加入至形狀集合的末端。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要加入的圖表類型。 |
| x | **float** | 新圖表的 x 座標，單位為點。 |
| y | **float** | 新圖表的 y 座標，單位為點。 |
| width | **float** | 圖表的寬度，單位為點。 |
| height | **float** | 圖表的高度，單位為點。 |

### 返回值

新建立的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 備註

以下範例說明如何在 PowerPoint [Presentation](../../presentation/) 中建立圖表。 
```cpp
// 實例化代表 PPTX 檔案的 Presentation 類別
auto pres = System::MakeObject<Presentation>();
// 存取第一張投影片
auto slide = pres->get_Slides()->idx_get(0);
// 新增一個帶有預設資料的圖表
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// 設定圖表標題
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// 設定第一個系列顯示數值
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// 設定圖表資料工作表的索引
int32_t defaultWorksheetIndex = 0;
// 取得圖表資料工作表
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// 刪除預設產生的系列與類別
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// 新增系列
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// 新增類別
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// 取得第一個圖表系列
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// 填充系列資料
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// 設定系列的填充顏色
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// 取得第二個圖表系列
series = chart->get_ChartData()->get_Series()->idx_get(1);
// 填充系列資料
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// 設定系列的填充顏色
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// 設定第一個標籤顯示類別名稱
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// 設定系列在第三個標籤顯示數值
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// 將 PPTX 檔案儲存至磁碟
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) 方法

建立一個新的圖表，使用範例系列資料和設定進行初始化，然後將其加入至形狀集合的末端。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要加入的圖表類型。 |
| x | **float** | 新圖表的 x 座標，單位為點。 |
| y | **float** | 新圖表的 y 座標，單位為點。 |
| width | **float** | 圖表的寬度，單位為點。 |
| height | **float** | 圖表的高度，單位為點。 |
| initWithSample | **bool** | True 表示使用範例系列資料和設定初始化新圖表；false 表示建立不含系列且僅有最小設定的圖表，從而加快建立速度。 |

### 返回值

新建立的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 另請參閱

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChart](../../../aspose.slides.charts/ichart/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)