---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description:
type: docs
url: /hi/aspose.slides/audioframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
[`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की array से shape geometry को अपडेट करता है। निर्देशांक shape के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। shape के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | ज्यामिति पथों की array |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | पथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पथ |

### देखें
* क्लास [`AudioFrame`](/slides/python-net/hi/aspose.slides/audioframe)
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)