---
title: get_image method
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API Reference
description: 
type: docs
url: /hi/aspose.slides/zoomobject/get_image/
weight: 30
---
## get_image(self) {#}
शेप थंबनेल लौटाता है।
डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है।

### रिटर्न
शेप थंबनेल।

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
शेप थंबनेल लौटाता है।

### रिटर्न
ShapeThumbnailBounds.Appearance उपयोग किए जाने पर और जब किसी shape में दृश्यमान तत्व नहीं होते हैं, तो Shape थंबनेल या None लौटता है।

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds) | Shape thumbnail बाउंड्स प्रकार। |
| scale_x | **float** | X स्केल |
| scale_y | **float** | Y स्केल |

### देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* एन्युमरेशन [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds)
* क्लास [`ZoomObject`](/slides/python-net/hi/aspose.slides/zoomobject)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)