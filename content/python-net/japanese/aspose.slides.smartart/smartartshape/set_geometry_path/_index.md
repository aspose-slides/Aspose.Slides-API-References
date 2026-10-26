---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/smartartshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
[`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトから形状ジオメトリを更新します。座標は形状の左上隅を基準とする必要があります。形状のタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。

```python
def set_geometry_path(self, geometry_path):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) | ジオメトリ パス |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | パスが見つかりません |
| **RuntimeError(Proxy error(ArgumentException))** | 空のパスが見つかりました |

### 参照
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* クラス [`SmartArtShape`](/slides/python-net/ja/aspose.slides.smartart/smartartshape)
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)