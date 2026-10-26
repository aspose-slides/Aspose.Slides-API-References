---
title: add_picture_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
指定された画像を含む新しい画像フレームを作成し、シェイプ コレクションの末尾に追加します。

### 戻り値

新しく作成された[`IPictureFrame`](/slides/python-net/ja/aspose.slides/ipictureframe)。

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)に含まれるシェイプの種類を指定します、<br/><br/>            ただし、すべての種類の線は除きます:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | 画像フレームの x 座標（ポイント単位）。 |
| y | **float** | 画像フレームの y 座標（ポイント単位）。 |
| width | **float** | 画像フレームの幅（ポイント単位）。 |
| height | **float** | 画像フレームの高さ（ポイント単位）。 |
| image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | 画像フレームに表示する[`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)。 |

### 参照
* クラス [`IPictureFrame`](/slides/python-net/ja/aspose.slides/ipictureframe)
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* 列挙体 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)