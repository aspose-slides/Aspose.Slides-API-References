---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
從 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) 物件更新形狀的幾何資訊。座標必須相對於形狀的左上角。將形狀的類型 ([`IGeometryShape.shape_type`](/slides/python-net/zh-hant/aspose.slides/igeometryshape/shape_type)) 更改為 [`ShapeType.CUSTOM`](/slides/python-net/zh-hant/aspose.slides/shapetype/CUSTOM)。

```python
def set_geometry_path(self, geometry_path):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath) | 幾何路徑 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 未找到路徑 |
| **RuntimeError(Proxy error(ArgumentException))** | 找到空的路徑 |

### 另請參閱
* 類別 [`IGeometryPath`](/slides/python-net/zh-hant/aspose.slides/igeometrypath)
* 類別 [`IGeometryShape`](/slides/python-net/zh-hant/aspose.slides/igeometryshape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)