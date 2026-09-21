---
title: set_geometry_path method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/geometryshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
[`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से आकार की ज्योमेट्री को अपडेट करता है। कोऑर्डिनेट्स आकार के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। आकार के प्रकार को ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) से [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।

```python
def set_geometry_path(self, geometry_path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) | ज्यामिति पाथ |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | पाथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पाथ मिला |

### संबंधित देखें
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)