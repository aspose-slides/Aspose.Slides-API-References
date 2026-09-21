---
title: set_geometry_path method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/videoframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
ژئومتری شکل را از شیء [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبی به گوشهٔ بالا سمت چپ شکل باشد.
تغییر نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) | Geometry path |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path found |

### موارد مرتبط
* کلاس [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath)
* کلاس [`VideoFrame`](/slides/python-net/fa/aspose.slides/videoframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)