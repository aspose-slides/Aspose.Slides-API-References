---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいオートシェイプを作成し、指定されたインデックスに形状コレクションに挿入し、デフォルトのテンプレート書式を適用します。
type: docs
weight: 339
url: /ja/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) メソッド


新しいオートシェイプを作成し、指定されたインデックスに形状コレクションに挿入し、デフォルトのテンプレート書式を適用します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいオートシェイプを挿入するゼロベースのインデックス。 |
| shapeType | [ShapeType](../../shapetype/) | 挿入するオートシェイプの[ShapeType](../../shapetype/)。 |
| x | **float** | シェイプのフレームのX座標（ポイント単位）。 |
| y | **float** | シェイプのフレームのY座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された[IAutoShape](../../iautoshape/)。

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) メソッド


新しいオートシェイプを作成し、指定されたインデックスに形状コレクションに挿入し、オプションでデフォルトのテンプレートスタイルで初期化します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | オートシェイプを挿入するゼロベースのインデックス。 |
| shapeType | [ShapeType](../../shapetype/) | 挿入するオートシェイプの[ShapeType](../../shapetype/)。 |
| x | **float** | シェイプのフレームのX座標（ポイント単位）。 |
| y | **float** | シェイプのフレームのY座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |
| createFromTemplate | **bool** | true の場合、デフォルトのテンプレートスタイル（空でない名前、シンプルなスタイル、中央揃えテキストを含む）を適用します。false の場合、すべてのプロパティを既定値に設定した状態でシェイプを作成します。 |

### 戻り値

新しく作成された[IAutoShape](../../iautoshape/)。

## 参照

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)