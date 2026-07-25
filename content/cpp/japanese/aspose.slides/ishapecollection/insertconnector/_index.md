---
title: InsertConnector()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいコネクタ形状を作成し、指定されたインデックスでシェイプ コレクションに挿入し、デフォルト テンプレート スタイリングを適用します。
type: docs
weight: 391
url: /ja/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) メソッド

新しいコネクタ形状を作成し、指定されたインデックスでシェイプ コレクションに挿入し、デフォルト テンプレート スタイリングを適用します。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | コネクタ形状を挿入する 0 から始まるインデックス。 |
| shapeType | [ShapeType](../../shapetype/) | 挿入するコネクタ形状の[ShapeType](../../shapetype/)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された [IConnector](../../iconnector/)。

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) メソッド

新しいコネクタ形状を作成し、指定されたインデックスでシェイプ コレクションに挿入し、オプションでデフォルト テンプレート スタイリングを適用します。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | コネクタ形状を挿入する 0 から始まるインデックス。 |
| shapeType | [ShapeType](../../shapetype/) | 挿入するコネクタ形状の[ShapeType](../../shapetype/)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |
| createFromTemplate | **bool** | True の場合、デフォルト テンプレート スタイリング（名前が空でなく、シンプルなスタイル）を適用します。false の場合、デフォルト プロパティ値でコネクタを作成します。 |

### 戻り値

新しく作成された [IConnector](../../iconnector/)。

## 参照

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IConnector](../../iconnector/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)