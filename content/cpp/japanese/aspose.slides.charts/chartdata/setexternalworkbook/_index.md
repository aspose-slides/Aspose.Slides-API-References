---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API リファレンス
description: 外部ブックブックをチャートのデータ ソースとして設定します。チャート データは対象ブックから更新されます。
type: docs
weight: 183
url: /ja/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) メソッド

外部ブックブックをチャートのデータ ソースとして設定します。[Chart](../../chart/) データは対象のブックから更新されます。

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 対象ブックへのパス |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) メソッド

外部ブックブックをチャートのデータ ソースとして設定します。

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 対象ブックへのパス |
| updateChartData | **bool** | 値が false の場合、ブックパスのみが更新されます。[Chart](../../chart/) データはロードされず、対象ブックから更新されません。対象ブックが存在しない場合や利用できない場合に使用できます。値が true の場合、チャート データが対象ブックから更新されます。 |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## 参照

* クラス [String](../../../system/string/)
* クラス [ChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)