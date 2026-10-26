---
title: set_geometry_paths method
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description:
type: docs
url: /hi/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
आकार की ज्यामिति को [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की array से अपडेट करता है। निर्देशांक shape के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। शेप ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) का प्रकार [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | ज्यामिति पाथ की array |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | कोई पाथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पाथ |

### देखें
* क्लास [`AutoShape`](/slides/python-net/hi/aspose.slides/autoshape)
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)