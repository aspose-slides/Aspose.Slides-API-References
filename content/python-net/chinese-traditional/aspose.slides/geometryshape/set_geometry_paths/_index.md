---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/geometryshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 陣列更新形狀的幾何資訊。座標必須相對於形狀的左上角。將形狀的類型 ([`GeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/geometryshape/shape_type)) 變更為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | 陣列幾何路徑 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 未找到路徑 |
| **RuntimeError(Proxy error(ArgumentException))** | 路徑為空 |

### 另請參閱
* 類別 [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape)
* 類別 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)