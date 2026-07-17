---
title: SetExternalWorkbook()
second_title: Aspose.Slides C++ API 参考
description: 将外部工作簿设置为图表的数据源。图表数据将从目标工作簿更新。
type: docs
weight: 196
url: /zh/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) 方法

将外部工作簿设置为图表的数据源。[Chart](../../chart/) 数据将从目标工作簿更新。

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
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

## IChartData::SetExternalWorkbook(System::String, bool) 方法

将外部工作簿设置为图表的数据源。

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 目标工作簿的路径 |
| updateChartData | **bool** | 如果值为 false，则只会更新工作簿路径。[Chart](../../chart/) 数据将不会从目标工作簿加载和更新。可在目标工作簿不存在或不可用时使用。如果值为 true，图表数据将从目标工作簿更新。 |

## 备注

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [IChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)