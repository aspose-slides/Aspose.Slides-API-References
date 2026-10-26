---
title: InsertChart()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいチャートを作成し、サンプル系列データと設定で初期化し、指定されたインデックスでシェイプコレクションに挿入します。
type: docs
weight: 92
url: /ja/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) メソッド

新しいチャートを作成し、サンプルの系列データと設定で初期化し、指定されたインデックスでシェイプコレクションに挿入します。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 作成するチャートのタイプ。 |
| x | **float** | 新しいチャートのX座標（ポイント単位）。 |
| y | **float** | 新しいチャートのY座標（ポイント単位）。 |
| width | **float** | 新しいチャートの幅（ポイント単位）。 |
| height | **float** | 新しいチャートの高さ（ポイント単位）。 |
| index | **int32_t** | シェイプコレクションに新しいチャートを挿入するゼロベースのインデックス。 |

### 戻り値

新しく作成された[Charts::IChart](../../../aspose.slides.charts/ichart/)。

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) メソッド

新しいチャートを作成し、サンプルの系列データと設定で初期化し、指定されたインデックスでシェイプコレクションに挿入します。

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 作成するチャートのタイプ。 |
| x | **float** | 新しいチャートのX座標（ポイント単位）。 |
| y | **float** | 新しいチャートのY座標（ポイント単位）。 |
| width | **float** | 新しいチャートの幅（ポイント単位）。 |
| height | **float** | 新しいチャートの高さ（ポイント単位）。 |
| index | **int32_t** | シェイプコレクションに新しいチャートを挿入するゼロベースのインデックス。 |
| initWithSample | **bool** | true の場合、サンプル系列データと設定で新しいチャートを初期化します。false の場合、系列なしで最小限の設定のみでチャートを作成し、作成が速くなります。 |

### 戻り値

新しく作成された[Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 関連項目

* 列挙体 [ChartType](../../../aspose.slides.charts/charttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChart](../../../aspose.slides.charts/ichart/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)