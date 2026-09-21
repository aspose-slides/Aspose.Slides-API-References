---
title: set_geometry_paths method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
आरे में [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) से आकार ज्यामिति को अपडेट करता है। निर्देशांक आकार के बाएँ ऊपर कोने के सापेक्ष होने चाहिए।
आकार ([`IGeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/igeometryshape/shape_type)) के प्रकार को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | ज्यामिति पथों की सरणी |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | कोई पथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पथ |



### देखें
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* क्लास [`IGeometryShape`](/slides/python-net/hi/aspose.slides/igeometryshape)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)