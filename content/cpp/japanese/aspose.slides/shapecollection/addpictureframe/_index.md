---
title: AddPictureFrame()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された画像を含む新しい画像フレームを作成し、シェイプコレクションの末尾に追加します。
type: docs
weight: 443
url: /ja/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) メソッド

指定された画像を含む新しい画像フレームを作成し、ShapeCollection の末尾に追加します。

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) に含まれるシェイプタイプを指定します。ただし、すべての種類の線は除きます:  

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
| x | **float** | 画像フレームの X 座標（ポイント単位）です。 |
| y | **float** | 画像フレームの Y 座標（ポイント単位）です。 |
| width | **float** | 画像フレームの幅（ポイント単位）です。 |
| height | **float** | 画像フレームの高さ（ポイント単位）です。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 画像フレームに表示する[IPPImage](../../ippimage/)です。 |

### 戻り値

新しく作成された[IPictureFrame](../../ipictureframe/)です。

## 参照

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)