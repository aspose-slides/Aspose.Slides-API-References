---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
从 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath) 对象更新形状几何。坐标必须相对于形状的左上角。 将形状的类型 ([`IGeometryShape.shape_type`](/slides/python-net/zh/aspose.slides/igeometryshape/shape_type)) 更改为 [`ShapeType.CUSTOM`](/slides/python-net/zh/aspose.slides/shapetype/CUSTOM)。


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
| **RuntimeError(Proxy error(ArgumentException))** | 发现空路径 |



### 另见
* 类 [`IGeometryPath`](/slides/python-net/zh/aspose.slides/igeometrypath)
* 类 [`IGeometryShape`](/slides/python-net/zh/aspose.slides/igeometryshape)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)