---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/pictureframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
[`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトからシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。


```python
def set_geometry_path(self, geometry_path):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) | ジオメトリパス |


### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | パスが見つかりません |
| **RuntimeError(Proxy error(ArgumentException))** | 空のパスが見つかりました |


### 参照
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* クラス [`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)