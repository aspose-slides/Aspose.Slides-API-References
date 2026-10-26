---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトの書式設定で新しい自動図形を作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 352
url: /ja/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method


自動図形をデフォルトの書式設定で作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 追加する自動図形の [ShapeType](../../shapetype/)。 |
| x | **float** | シェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | シェイプのフレームの y 座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |

### 戻り値

新しく作成された [IAutoShape](../../iautoshape/)。

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method


自動図形を作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルト テンプレートの書式設定で初期化できます。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 追加する自動図形の [ShapeType](../../shapetype/)。 |
| x | **float** | シェイプのフレームの x 座標（ポイント単位）。 |
| y | **float** | シェイプのフレームの y 座標（ポイント単位）。 |
| width | **float** | シェイプのフレームの幅（ポイント単位）。 |
| height | **float** | シェイプのフレームの高さ（ポイント単位）。 |
| createFromTemplate | **bool** | true の場合、新しいシェイプにデフォルト テンプレート スタイル（シンプル スタイル、中央揃えテキスト、空でない名前）を適用します。false の場合、すべてのプロパティがデフォルト値に設定されたシェイプを作成します。 |

### 戻り値

新しく作成された [IAutoShape](../../iautoshape/)。

## 関連項目

* 列挙型 [ShapeType](../../shapetype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)