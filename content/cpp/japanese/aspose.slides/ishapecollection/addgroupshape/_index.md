---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい空のグループ シェイプを作成し、シェイプ コレクションの末尾に追加します。グループのフレームは、追加されたシェイプに合わせて自動的に調整されます。
type: docs
weight: 352
url: /ja/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() メソッド

新しい空のグループシェイプを作成し、シェイプコレクションの末尾に追加します。グループのフレームは、追加されたシェイプに合わせて自動的に調整されます。

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### 戻り値

新しく作成された [IGroupShape](../../igroupshape/)。

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) メソッド

指定された SVG 画像を個別のシェイプに変換し、新しいグループシェイプを作成して、シェイプコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | ベクターコンテンツを含む [ISvgImage](../../isvgimage/) をシェイプに変換します。 |
| x | **float** | ポイント単位のグループのフレームの x 座標。 |
| y | **float** | ポイント単位のグループのフレームの y 座標。 |
| width | **float** | ポイント単位のグループのフレームの幅。 |
| height | **float** | ポイント単位のグループのフレームの高さ。 |

### 戻り値

新しく作成された [IGroupShape](../../igroupshape/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IGroupShape](../../igroupshape/)
* クラス [IShapeCollection](../)
* クラス [ISvgImage](../../isvgimage/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)