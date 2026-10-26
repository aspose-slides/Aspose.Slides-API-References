---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/autoshape/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
从 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。将形状的类型 ([`GeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/geometryshape/shape_type)) 更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。

```python
def set_geometry_path(self, geometry_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) | 几何路径 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 未找到路径 |
| **RuntimeError(Proxy error(ArgumentException))** | 找到空路径 |

### 另见
* 类 [`AutoShape`](/slides/python-net/zh/aspose.slides/autoshape)
* 类 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)