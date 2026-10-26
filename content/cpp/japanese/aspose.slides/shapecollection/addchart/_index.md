---
title: AddChart()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいチャートを作成し、サンプル系列データと設定で初期化して、シェイプコレクションの末尾に追加します。
type: docs
weight: 66
url: /ja/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) メソッド

新しいチャートを作成し、サンプル系列データと設定で初期化して、シェイプコレクションの末尾に追加します。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 追加するチャートのタイプ。 |
| x | **float** | 新しいチャートの x 座標（ポイント単位）。 |
| y | **float** | 新しいチャートの y 座標（ポイント単位）。 |
| width | **float** | チャートの幅（ポイント単位）。 |
| height | **float** | チャートの高さ（ポイント単位）。 |

### 戻り値

新しく作成された [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 備考

次の例は、PowerPoint [Presentation](../../presentation/) で Chart を作成する方法を示しています。 
```cpp
// PPTX ファイルを表す Presentation クラスのインスタンスを作成します
auto pres = System::MakeObject<Presentation>();
// 最初のスライドにアクセスします
auto slide = pres->get_Slides()->idx_get(0);
// デフォルトデータでチャートを追加します
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// チャートのタイトルを設定します
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// 最初の系列に値を表示するよう設定します
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// チャートデータシートのインデックスを設定します
int32_t defaultWorksheetIndex = 0;
// チャートデータのワークシートを取得します
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// デフォルトで生成された系列とカテゴリを削除します
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// 新しい系列を追加します
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// 新しいカテゴリを追加します
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// 最初のチャート系列を取得します
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// 系列データを設定します
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// 系列の塗りつぶし色を設定します
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// 2 番目のチャート系列を取得します
series = chart->get_ChartData()->get_Series()->idx_get(1);
// 系列データを設定します
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// 系列の塗りつぶし色を設定します
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// 最初のラベルにカテゴリ名を表示するよう設定します
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// 3 番目のラベルに値を表示するよう系列を設定します
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// PPTX ファイルをディスクに保存します
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) メソッド

新しいチャートを作成し、サンプル系列データと設定で初期化して、シェイプコレクションの末尾に追加します。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 追加するチャートのタイプ。 |
| x | **float** | 新しいチャートの x 座標（ポイント単位）。 |
| y | **float** | 新しいチャートの y 座標（ポイント単位）。 |
| width | **float** | チャートの幅（ポイント単位）。 |
| height | **float** | チャートの高さ（ポイント単位）。 |
| initWithSample | **bool** | true は、新しいチャートをサンプル系列データと設定で初期化します。false は、系列なしで最小限の設定だけでチャートを作成し、作成を高速化します。 |

### 戻り値

新しく作成された [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 関連項目

* 列挙 [ChartType](../../../aspose.slides.charts/charttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChart](../../../aspose.slides.charts/ichart/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)