---
title: set_geometry_paths method
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/geometryshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
आकार की ज्यामिति को [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की सरणी से अपडेट करता है। निर्देशांक को आकार के बाएँ शीर्ष कोने के सापेक्ष होना चाहिए।
आकार के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | ज्यामिति पथों की सरणी |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | कोई पथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पथ |



### संबंधित देखें
* क्लास [`GeometryShape`](/slides/python-net/hi/aspose.slides/geometryshape)
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)