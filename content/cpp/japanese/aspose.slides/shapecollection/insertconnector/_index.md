---
title: InsertConnector()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいコネクタ シェイプを作成し、指定されたインデックスに shape collection に挿入し、デフォルトのテンプレート スタイルを適用します。
type: docs
weight: 430
url: /ja/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) メソッド

新しいコネクタ シェイプを作成し、指定したインデックスに shape collection に挿入し、デフォルトのテンプレート スタイルを適用します。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | コネクタ シェイプを挿入するゼロベースのインデックス。 |
| shapeType | [ShapeType](../../shapetype/) | 挿入するコネクタ シェイプの [ShapeType](../../shapetype/)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された [IConnector](../../iconnector/)。

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) メソッド

新しいコネクタ シェイプを作成し、指定したインデックスに shape collection に挿入し、必要に応じてデフォルトのテンプレート スタイルを適用します。

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | コネクタ シェイプを挿入するゼロベースのインデックス。 |
| shapeType | [ShapeType](../../shapetype/) | 挿入するコネクタ シェイプの [ShapeType](../../shapetype/)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |
| createFromTemplate | **bool** | True はデフォルトのテンプレート スタイル（空でない名前、シンプルなスタイル）を適用し、false はデフォルトのプロパティ値でコネクタを作成します。 |

### 戻り値

新しく作成された [IConnector](../../iconnector/)。

## 参照

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IConnector](../../iconnector/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)