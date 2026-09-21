---
title: set_geometry_paths method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides/pictureframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
आरेख के [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath) के एरे से आकार की ज्यामिति को अपडेट करता है। निर्देशांक आकार के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`GeometryShape.shape_type`](/slides/python-net/hi/aspose.slides/geometryshape/shape_type)) को [`ShapeType.CUSTOM`](/slides/python-net/hi/aspose.slides/shapetype/CUSTOM) में बदलता है।

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | ज्यामिति पाथ्स की एरे |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | पथ नहीं मिला |
| **RuntimeError(Proxy error(ArgumentException))** | खाली पथ |

### संबंधित देखें
* क्लास [`IGeometryPath`](/slides/python-net/hi/aspose.slides/igeometrypath)
* क्लास [`PictureFrame`](/slides/python-net/hi/aspose.slides/pictureframe)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)