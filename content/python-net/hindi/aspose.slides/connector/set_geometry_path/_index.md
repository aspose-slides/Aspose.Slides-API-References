---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/connector/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
आकार की ज्यामिति को [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) वस्तु से अपडेट करता है। निर्देशांक को आकार के बाएँ शीर्ष कोने के सापेक्ष होना चाहिए। आकार के प्रकार को ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) से [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।

```python
def set_geometry_path(self, geometry_path):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) | ज्यामिति पथ |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | कोई पथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पथ मिला |



### संबंधित देखें
* क्लास [`Connector`](/slides/python-net/hi/aspose.slides/connector)
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)