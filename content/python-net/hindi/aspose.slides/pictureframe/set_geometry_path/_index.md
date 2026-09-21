---
title: set_geometry_path method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/pictureframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
[`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) वस्तु से आकार की ज्यामिति को अपडेट करता है। निर्देशांक आकार के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। आकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) के प्रकार को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।

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
* क्लास [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)