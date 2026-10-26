---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 陣列更新形狀的幾何。座標必須相對於形狀的左上角。將形狀 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 的類型更改為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | 幾何路徑陣列 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 未找到路徑 |
| **RuntimeError(Proxy error(ArgumentException))** | 路徑為空 |

### 參見
* 類別 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath)
* 類別 [`SmartArtShape`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape)
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 函式庫 [`Aspose.Slides`](/slides/python-net)