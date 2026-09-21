---
title: set_geometry_paths method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/pictureframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
از آرایه‌ای از [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) هندسهٔ شکل را به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالای چپ شکل نسبی باشد. نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌یابد.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | آرایه مسیرهای هندسه |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | مسیر یافت نشد |
| **RuntimeError(Proxy error(ArgumentException))** | مسیر خالی |

### موارد دیگر
* کلاس [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath)
* کلاس [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)