---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.smartart/smartartshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
[`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) ऑब्जेक्ट से आकार की ज्यामिति को अपडेट करता है। Coordinates must be relative to the left
             top corner of the shape.
             आकार का प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदल देता है।


```python
def set_geometry_path(self, geometry_path):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) | Geometry path |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | कोई पथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पथ मिला |



### देखें भी
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* क्लास [`SmartArtShape`](/slides/python-net/hi/aspose.slides.smartart/smartartshape)
* मॉड्यूल [`aspose.slides.smartart`](/slides/python-net/hi/aspose.slides.smartart)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)