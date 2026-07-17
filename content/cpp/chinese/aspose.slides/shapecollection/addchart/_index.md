---
title: AddChart()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新的图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。
type: docs
weight: 66
url: /zh/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) 方法

创建一个新的图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要添加的图表类型。 |
| x | **float** | 新图表的 x 坐标，单位为点。 |
| y | **float** | 新图表的 y 坐标，单位为点。 |
| width | **float** | 图表的宽度，单位为点。 |
| height | **float** | 图表的高度，单位为点。 |

### 返回值

新创建的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 备注

下面的示例展示了如何在 PowerPoint [Presentation](../../presentation/) 中创建 Chart。

```cpp
// 实例化表示 PPTX 文件的 Presentation 类
auto pres = System::MakeObject<Presentation>();
// 访问第一张幻灯片
auto slide = pres->get_Slides()->idx_get(0);
// 添加一个带有默认数据的图表
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// 设置图表标题
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// 设置第一系列显示数值
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// 设置图表数据工作表的索引
int32_t defaultWorksheetIndex = 0;
// 获取图表数据工作表
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// 删除默认生成的系列和类别
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// 添加新系列
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// 添加新类别
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// 获取第一条图表系列
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// 填充系列数据
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// 设置系列的填充颜色
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// 获取第二条图表系列
series = chart->get_ChartData()->get_Series()->idx_get(1);
// 填充系列数据
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// 设置系列的填充颜色
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// 设置第一个标签显示类别名称
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// 设置系列在第三个标签显示数值
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// 将 PPTX 文件保存到磁盘
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) 方法

创建一个新的图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 要添加的图表类型。 |
| x | **float** | 新图表的 x 坐标，单位为点。 |
| y | **float** | 新图表的 y 坐标，单位为点。 |
| width | **float** | 图表的宽度，单位为点。 |
| height | **float** | 图表的高度，单位为点。 |
| initWithSample | **bool** | True 表示使用示例系列数据和设置初始化新图表；false 表示创建没有系列且仅有最小设置的图表，以加快创建速度。 |

### 返回值

新创建的 [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 另见

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)