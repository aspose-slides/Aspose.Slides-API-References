---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
配列 [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) からシェイプのジオメトリを更新します。座標はシェイプの左上隅に対して相対的である必要があります。シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | ジオメトリ パスの配列 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | パスが見つかりません |
| **RuntimeError(Proxy error(ArgumentException))** | 空のパス |

### 参照
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* クラス [`SmartArtShape`](/slides/python-net/ja/aspose.slides.smartart/smartartshape)
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)