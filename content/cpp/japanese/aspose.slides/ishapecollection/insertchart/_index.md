---
title: InsertChart()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいチャートを作成し、サンプル系列データと設定で初期化し、指定されたインデックスにシェイプコレクションへ挿入します。
type: docs
weight: 53
url: /ja/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) メソッド

新しいチャートを作成し、サンプル系列データと設定で初期化し、指定されたインデックスにシェイプコレクションへ挿入します。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 作成するチャートの種類。 |
| x | **float** | 新しいチャートの x 座標（ポイント）。 |
| y | **float** | 新しいチャートの y 座標（ポイント）。 |
| width | **float** | 新しいチャートの幅（ポイント）。 |
| height | **float** | 新しいチャートの高さ（ポイント）。 |
| index | **int32_t** | シェイプコレクション内で新しいチャートを挿入するゼロベースのインデックス。 |

### 戻り値

新しく作成された[Charts::IChart](../../../aspose.slides.charts/ichart/)です。

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) メソッド

新しいチャートを作成し、サンプル系列データと設定で初期化し、指定されたインデックスにシェイプコレクションへ挿入します。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 作成するチャートの種類。 |
| x | **float** | 新しいチャートの x 座標（ポイント）。 |
| y | **float** | 新しいチャートの y 座標（ポイント）。 |
| width | **float** | 新しいチャートの幅（ポイント）。 |
| height | **float** | 新しいチャートの高さ（ポイント）。 |
| index | **int32_t** | シェイプコレクション内で新しいチャートを挿入するゼロベースのインデックス。 |
| initWithSample | **bool** | true の場合、新しいチャートをサンプル系列データと設定で初期化します。false の場合、系列なしで最小限の設定だけでチャートを作成し、作成が高速になります。 |

### 戻り値

新しく作成された[Charts::IChart](../../../aspose.slides.charts/ichart/)です。

## 参照

* 列挙型 [ChartType](../../../aspose.slides.charts/charttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChart](../../../aspose.slides.charts/ichart/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)