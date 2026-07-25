---
title: AddChart()
second_title: Aspose.Slides for C++ APIリファレンス
description: 新しいチャートを作成し、サンプルシリーズデータと設定で初期化し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 27
url: /ja/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) メソッド


新しいチャートを作成し、サンプルシリーズ データと設定で初期化し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 追加するチャートのタイプ。 |
| x | **float** | 新しいチャートの X 座標 (単位はポイント)。 |
| y | **float** | 新しいチャートの Y 座標 (単位はポイント)。 |
| width | **float** | チャートの幅 (単位はポイント)。 |
| height | **float** | チャートの高さ (単位はポイント)。 |

### 戻り値

新しく作成された [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) メソッド


新しいチャートを作成し、サンプルシリーズ データと設定で初期化し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 追加するチャートのタイプ。 |
| x | **float** | 新しいチャートの X 座標 (単位はポイント)。 |
| y | **float** | 新しいチャートの Y 座標 (単位はポイント)。 |
| width | **float** | チャートの幅 (単位はポイント)。 |
| height | **float** | チャートの高さ (単位はポイント)。 |
| initWithSample | **bool** | true の場合、新しいチャートをサンプルシリーズ データと設定で初期化します。false の場合、シリーズなしで最小限の設定のみでチャートを作成し、作成が高速になります。 |

### 戻り値

新しく作成された [Charts::IChart](../../../aspose.slides.charts/ichart/)。

## 参照

* 列挙型 [ChartType](../../../aspose.slides.charts/charttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IChart](../../../aspose.slides.charts/ichart/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)