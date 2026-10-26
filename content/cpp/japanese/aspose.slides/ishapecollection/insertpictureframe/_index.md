---
title: InsertPictureFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された画像を含む新しい画像フレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。
type: docs
weight: 417
url: /ja/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) メソッド


指定した画像を含む新しい画像フレームを作成し、指定したインデックスでシェイプコレクションに挿入します。

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 画像フレームを挿入するゼロベースのインデックス。 |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) に含まれる形状タイプを指定します。ただし、すべての種類の線は除きます: [ShapeType::Line](../../shapetype/), [ShapeType::StraightConnector1](../../shapetype/), [ShapeType::BentConnector2](../../shapetype/), [ShapeType::BentConnector3](../../shapetype/), [ShapeType::BentConnector4](../../shapetype/), [ShapeType::BentConnector5](../../shapetype/), [ShapeType::CurvedConnector2](../../shapetype/), [ShapeType::CurvedConnector3](../../shapetype/), [ShapeType::CurvedConnector4](../../shapetype/), [ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | 画像フレームの x 座標（ポイント単位）。 |
| y | **float** | 画像フレームの y 座標（ポイント単位）。 |
| width | **float** | 画像フレームの幅（ポイント単位）。 |
| height | **float** | 画像フレームの高さ（ポイント単位）。 |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 画像フレームに表示する [IPPImage](../../ippimage/)。 |

### 戻り値

新しく作成された [IPictureFrame](../../ipictureframe/)。

## 関連項目

* 列挙型 [ShapeType](../../shapetype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPictureFrame](../../ipictureframe/)
* クラス [IPPImage](../../ippimage/)
* クラス [IShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)