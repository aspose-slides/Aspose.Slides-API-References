---
title: set_geometry_paths method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/videoframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
ژئومتری شکل را از آرایهٔ [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ چپ بالای شکل نسبی باشند. نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | آرایهٔ مسیرهای ژئومتری |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | هیچ مسیری یافت نشد |
| **RuntimeError(Proxy error(ArgumentException))** | مسیر خالی |

### مطالب مرتبط
* کلاس [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath)
* کلاس [`VideoFrame`](/slides/python-net/fa/aspose.slides/videoframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)