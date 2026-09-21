---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/videoframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
शेप ज्यामिति को [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक को शैप के बाएँ ऊपर कोने के सापेक्ष होना चाहिए।  
शेप के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।

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
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* क्लास [`VideoFrame`](/slides/python-net/hi/aspose.slides/videoframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)