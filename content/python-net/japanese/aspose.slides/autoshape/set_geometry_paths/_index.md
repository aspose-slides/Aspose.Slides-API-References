---
title: set_geometry_paths method
second_title: Python 用 Aspose.Slides の .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
[`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) の配列からシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ（[`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)）を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | ジオメトリパスの配列 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | パスが見つかりません |
| **RuntimeError(Proxy error(ArgumentException))** | パスが空です |

### 参照
* クラス [`AutoShape`](/slides/python-net/ja/aspose.slides/autoshape)
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)