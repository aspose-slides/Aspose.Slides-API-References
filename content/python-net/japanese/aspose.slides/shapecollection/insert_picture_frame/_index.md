---
title: insert_picture_frame method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
指定された画像を含む新しいピクチャーフレームを作成し、指定されたインデックスでシェイプコレクションに挿入します。

### 戻り値

新しく作成された[`IPictureFrame`](/slides/python-net/ja/aspose.slides/ipictureframe)。

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | **int** | ピクチャーフレームを挿入するゼロベースのインデックスです。 |
| shape_type | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)に含まれるシェイプタイプを指定します,<br/><br/>            ただし、すべての種類の線は除外されます:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | ピクチャーフレームの x 座標（ポイント単位）。 |
| y | **float** | ピクチャーフレームの y 座標（ポイント単位）。 |
| width | **float** | ピクチャーフレームの幅（ポイント単位）。 |
| height | **float** | ピクチャーフレームの高さ（ポイント単位）。 |
| image | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | ピクチャーフレームに表示する[`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)。 |

### 参照
* クラス [`IPictureFrame`](/slides/python-net/ja/aspose.slides/ipictureframe)
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`ShapeCollection`](/slides/python-net/ja/aspose.slides/shapecollection)
* 列挙型 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)