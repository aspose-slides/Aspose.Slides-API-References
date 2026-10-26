---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいオートシェイプを作成し、指定されたインデックスにシェイプコレクションへ挿入して、デフォルトのテンプレート書式を適用します。
type: docs
weight: 378
url: /ja/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) メソッド

新しいオートシェイプを作成し、指定されたインデックスにシェイプコレクションへ挿入し、デフォルトのテンプレート書式を適用します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいオートシェイプを挿入するゼロベースのインデックスです。 |
| shapeType | [ShapeType](../../shapetype/) | 挿入するオートシェイプの[ShapeType](../../shapetype/)です。 |
| x | **float** | シェイプ\\u2019s のフレームの x 座標（ポイント単位）です。 |
| y | **float** | シェイプ\\u2019s のフレームの y 座標（ポイント単位）です。 |
| width | **float** | シェイプ\\u2019s のフレームの幅（ポイント単位）です。 |
| height | **float** | シェイプ\\u2019s のフレームの高さ（ポイント単位）です。 |

### 戻り値

新しく作成された[IAutoShape](../../iautoshape/)です。

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) メソッド

新しいオートシェイプを作成し、指定されたインデックスにシェイプコレクションへ挿入します。オプションでデフォルトのテンプレートスタイルで初期化することもできます。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | オートシェイプを挿入するゼロベースのインデックスです。 |
| shapeType | [ShapeType](../../shapetype/) | 挿入するオートシェイプの[ShapeType](../../shapetype/)です。 |
| x | **float** | シェイプ\\u2019s のフレームの x 座標（ポイント単位）です。 |
| y | **float** | シェイプ\\u2019s のフレームの y 座標（ポイント単位）です。 |
| width | **float** | シェイプ\\u2019s のフレームの幅（ポイント単位）です。 |
| height | **float** | シェイプ\\u2019s のフレームの高さ（ポイント単位）です。 |
| createFromTemplate | **bool** | true の場合、デフォルトのテンプレートスタイル（空でない名前、シンプルなスタイル、センタリングされたテキストを含む）を適用します。false の場合、すべてのプロパティがデフォルトに設定された状態でシェイプを作成します。 |

### 戻り値

新しく作成された[IAutoShape](../../iautoshape/)です。

## 関連項目

* 列挙型 [ShapeType](../../shapetype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)