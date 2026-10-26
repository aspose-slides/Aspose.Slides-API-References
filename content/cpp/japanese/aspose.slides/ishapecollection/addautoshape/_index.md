---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトの書式設定で新しいオートシェイプを作成し、シェイプコレクションの末尾に追加します。
type: docs
weight: 313
url: /ja/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) メソッド

デフォルトの書式設定で新しいオートシェイプを作成し、シェイプコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 追加するオートシェイプの[ShapeType](../../shapetype/)。 |
| x | **float** | シェイプのフレームのx座標（ポイント単位）。 |
| y | **float** | シェイプのフレームのy座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された[IAutoShape](../../iautoshape/)。

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) メソッド

新しいオートシェイプを作成し、シェイプコレクションの末尾に追加します。オプションでデフォルトのテンプレート書式設定を使用して初期化することもできます。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 追加するオートシェイプの[ShapeType](../../shapetype/)。 |
| x | **float** | シェイプのフレームのx座標（ポイント単位）。 |
| y | **float** | シェイプのフレームのy座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |
| createFromTemplate | **bool** | True の場合、新しいシェイプにデフォルトのテンプレートスタイル（シンプルなスタイル、中央揃えテキスト、空でない名前）を適用します。false の場合、すべてのプロパティがデフォルト値に設定された状態でシェイプを作成します。 |

### 戻り値

新しく作成された[IAutoShape](../../iautoshape/)。

## 参照

* 列挙型 [ShapeType](../../shapetype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)