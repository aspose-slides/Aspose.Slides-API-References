---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/videoframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
从 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 数组更新形状几何。坐标必须相对于形状的左上角。将形状的类型 ([`GeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/geometryshape/shape_type)) 更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | 几何路径数组 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 未找到路径 |
| **RuntimeError(Proxy error(ArgumentException))** | 路径为空 |

### 另见
* 类 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath)
* 类 [`VideoFrame`](/slides/python-net/zh/aspose.slides/videoframe)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)