---
title: AddConnector()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトテンプレートのスタイルを適用した新しいコネクタシェイプを作成し、シェイプコレクションの末尾に追加します。
type: docs
weight: 378
url: /ja/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) メソッド


デフォルトテンプレートのスタイルを適用した新しいコネクタシェイプを作成し、シェイプコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 追加するコネクタシェイプの[ShapeType](../../shapetype/)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された[IConnector](../../iconnector/)。

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) メソッド


新しいコネクタシェイプを作成し、シェイプコレクションの末尾に追加します。オプションでデフォルトテンプレートのスタイルを適用できます。

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 作成するコネクタシェイプの[ShapeType](../../shapetype/)。 |
| x | **float** | コネクタのフレームの x 座標（ポイント単位）。 |
| y | **float** | コネクタのフレームの y 座標（ポイント単位）。 |
| width | **float** | コネクタのフレームの幅（ポイント単位）。 |
| height | **float** | コネクタのフレームの高さ（ポイント単位）。 |
| createFromTemplate | **bool** | True の場合はデフォルトテンプレートのスタイル（名前が空でなくシンプルなスタイル）を適用し、false の場合はデフォルトのプロパティ値でコネクタを作成します。 |

### 戻り値

新しく作成された[IConnector](../../iconnector/)。

## 参照

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IConnector](../../iconnector/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)