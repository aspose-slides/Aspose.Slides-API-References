---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API 参考
description: 将外部工作簿设置为图表的数据源。图表数据将从目标工作簿更新。
type: docs
weight: 183
url: /zh/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) 方法

将外部工作簿设置为图表的数据源。[Chart](../../chart/) 数据将从目标工作簿更新。

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 目标工作簿的路径 |
## 备注

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) 方法

将外部工作簿设置为图表的数据源。

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 目标工作簿的路径 |
| updateChartData | **bool** | 如果值为 false，仅会更新工作簿路径。[Chart](../../chart/) 数据将不会从目标工作簿加载和更新。可在目标工作簿不存在或不可用时使用。如果值为 true，图表数据将从目标工作簿更新。 |
## 备注

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## 另请参见

* 类 [String](../../../system/string/)
* 类 [ChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)