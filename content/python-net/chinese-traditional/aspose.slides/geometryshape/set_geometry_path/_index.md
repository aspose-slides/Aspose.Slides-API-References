---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/geometryshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左上角。將形狀的類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) | 幾何路徑 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 找不到路徑 |
| **RuntimeError(Proxy error(ArgumentException))** | 找到空的路徑 |

### 參見
* 類別 [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape)
* 類別 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)