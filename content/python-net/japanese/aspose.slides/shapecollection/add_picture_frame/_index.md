---
title: add_picture_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
指定された画像を含む新しい画像フレームを作成し、シェイプコレクションの末尾に追加します。

### Returns
新しく作成された[`IPictureFrame`](/slides/python-net/ja/aspose.slides/ipictureframe)。

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) に含まれるシェイプタイプを指定します、<br/><br/>            except for all kinds of lines:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | 画像フレームの x 座標（ポイント単位）です。 |
| y | **float** | 画像フレームの y 座標（ポイント単位）です。 |
| width | **float** | 画像フレームの幅（ポイント単位）です。 |
| height | **float** | 画像フレームの高さ（ポイント単位）です。 |
| image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | 画像フレームに表示する[`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)です。 |

### 参照
* クラス [`IPictureFrame`](/slides/python-net/ja/aspose.slides/ipictureframe)
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* 列挙型 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)