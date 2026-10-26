---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/videoframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
[`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) の配列からシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | ジオメトリパスの配列 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | パスが見つかりません |
| **RuntimeError(Proxy error(ArgumentException))** | パスが空です |

### See Also
* クラス [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath)
* クラス [`VideoFrame`](/slides/python-net/ja/aspose.slides/videoframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)