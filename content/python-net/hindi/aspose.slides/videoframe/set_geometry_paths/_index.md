---
title: set_geometry_paths method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/videoframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
[`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) की एरे से shape geometry को अपडेट करता है। निर्देशांक shape के बाएँ
             ऊपर कोने के सापेक्ष होने चाहिए।
             shape ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) का प्रकार [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | ज्यामिति पथों की एरे |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | कोई पथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पथ |



### संबंधित देखें
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* क्लास [`VideoFrame`](/slides/python-net/hi/aspose.slides/videoframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)