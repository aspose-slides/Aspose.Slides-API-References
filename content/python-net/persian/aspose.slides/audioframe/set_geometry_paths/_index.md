---
title: set_geometry_paths method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/audioframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
هندسه شکل را از آرایه‌ای از [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath) به‌روز می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل نسبی باشند. نوع شکل ([`GeometryShape.shape_type`](/slides/python-net/fa/aspose.slides/geometryshape/shape_type)) را به [`ShapeType.CUSTOM`](/slides/python-net/fa/aspose.slides/shapetype/CUSTOM) تغییر می‌دهد.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | آرایه‌ی مسیرهای هندسی |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | مسیر یافت نشد |
| **RuntimeError(Proxy error(ArgumentException))** | مسیر خالی |

### موارد مرتبط
* کلاس [`AudioFrame`](/slides/python-net/fa/aspose.slides/audioframe)
* کلاس [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)