---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.smartart/smartartshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
使用 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。将形状的类型 ([`GeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/geometryshape/shape_type)) 更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。


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



### 参见
* 类 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath)
* 类 [`SmartArtShape`](/slides/python-net/zh/aspose.slides.smartart/smartartshape)
* 模块 [`aspose.slides.smartart`](/slides/python-net/zh/aspose.slides.smartart)
* 库 [`Aspose.Slides`](/slides/python-net)