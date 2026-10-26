---
title: AddPictureFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された画像を含む新しい画像フレームを作成し、シェイプコレクションの末尾に追加します。
type: docs
weight: 404
url: /ja/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) メソッド


指定された画像を含む新しい画像フレームを作成し、シェイプコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) に含まれるシェイプタイプを指定しますが、すべての種類のラインは除外されます:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | 画像フレームの x 座標（ポイント単位）。 |
| y | **float** | 画像フレームの y 座標（ポイント単位）。 |
| width | **float** | 画像フレームの幅（ポイント単位）。 |
| height | **float** | 画像フレームの高さ（ポイント単位）。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 画像フレームに表示する [IPPImage](../../ippimage/)。 |

### 戻り値

新しく作成された [IPictureFrame](../../ipictureframe/)。

## 参照

* 列挙型 [ShapeType](../../shapetype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPictureFrame](../../ipictureframe/)
* クラス [IPPImage](../../ippimage/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)