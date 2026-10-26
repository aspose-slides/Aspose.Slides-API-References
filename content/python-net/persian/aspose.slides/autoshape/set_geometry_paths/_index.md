---
title: set_geometry_paths method
second_title: Aspose.Slides برای Python از طریق مرجع API .NET
description: 
type: docs
url: /fa/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
هندسه شکل را از آرایه‌ای از [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ چپ بالای شکل باشند. نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌یابد.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | آرایه‌ای از مسیرهای هندسی |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | مسیر پیدا نشد |
| **RuntimeError(Proxy error(ArgumentException))** | مسیر خالی |

### موارد مرتبط
* کلاس [`AutoShape`](/slides/python-net/fa/aspose.slides/autoshape)
* کلاس [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)