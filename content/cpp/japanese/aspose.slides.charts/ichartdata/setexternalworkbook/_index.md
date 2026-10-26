---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API リファレンス
description: 外部ブックブックをチャートのデータ ソースとして設定します。チャート データは対象のブックブックから更新されます。
type: docs
weight: 196
url: /ja/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) method

チャートのデータ ソースとして外部ブックブックを設定します。[Chart](../../chart/) データは対象のブックブックから更新されます。

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 対象ブックブックへのパス |
## 備考

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) method

チャートのデータ ソースとして外部ブックブックを設定します。

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 対象ブックブックへのパス |
| updateChartData | **bool** | 値が false の場合、ブックブックのパスのみが更新されます。[Chart](../../chart/) データは読み込まれず、対象のブックブックから更新されません。対象ブックブックが存在しない、または使用できない場合に使用できます。値が true の場合、チャート データは対象のブックブックから更新されます。 |
## 備考

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## 関連項目

* クラス [String](../../../system/string/)
* クラス [IChartData](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* ライブラリ [Aspose.Slides](../../../)