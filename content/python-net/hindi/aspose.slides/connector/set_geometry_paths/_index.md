---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/connector/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
शेप ज्योमेट्री को [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की एरे से अपडेट करता है। निर्देशांक shape के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। shape के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | एरे ज्योमेट्री पाथ्स |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | कोई पाथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पाथ |

### देखें भी
* क्लास [`Connector`](/slides/python-net/hi/aspose.slides/connector)
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)