---
title: SetExternalWorkbook()
second_title: Aspose.Slides C++ API 參考
description: 將外部活頁簿設定為圖表的資料來源。圖表資料將從目標活頁簿更新。
type: docs
weight: 183
url: /zh-hant/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) 方法

將外部活頁簿設定為圖表的資料來源。 [Chart](../../chart/) 資料將從目標活頁簿更新。

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 目標活頁簿的路徑 |

## 備註

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) 方法

將外部活頁簿設定為圖表的資料來源。

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 目標活頁簿的路徑 |
| updateChartData | **bool** | 如果值為 false，僅會更新活頁簿路徑。 [Chart](../../chart/) 資料將不會從目標活頁簿載入並更新。 可在目標活頁簿不存在或無法取得時使用。 如果值為 true，圖表資料將從目標活頁簿更新。 |

## 備註

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [ChartData](../)
* 名稱空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)