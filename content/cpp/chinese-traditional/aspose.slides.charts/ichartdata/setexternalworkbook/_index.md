---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API 參考文件
description: 將外部工作簿設定為圖表的資料來源。圖表資料將從目標工作簿更新。
type: docs
weight: 196
url: /zh-hant/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) 方法


將外部工作簿設為圖表的資料來源。[Chart](../../chart/) 資料將從目標工作簿更新。

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 目標工作簿的路徑 |
## 備註




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) 方法


將外部工作簿設為圖表的資料來源。

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 目標工作簿的路徑 |
| updateChartData | **bool** | 如果值為 false，僅會更新工作簿路徑。[Chart](../../chart/) 資料不會從目標工作簿載入和更新。可在目標工作簿不存在或不可用時使用。如果值為 true，圖表資料將從目標工作簿更新。 |
## 備註




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## 參見

* 類別 [String](../../../system/string/)
* 類別 [IChartData](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)