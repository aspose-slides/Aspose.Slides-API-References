---
title: get_image method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/ishape/get_image/
weight: 30
---
## get_image(self) {#}
shape thumbnail लौटाता है।
ShapeThumbnailBounds.Shape shape thumbnail bounds type डिफ़ॉल्ट रूप से उपयोग किया जाता है।

### Returns
Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
shape thumbnail लौटाता है।

### Returns
Shape thumbnail या None जब ShapeThumbnailBounds.Appearance उपयोग किया जाता है और shape में दृश्यमान तत्व नहीं होते हैं।

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X स्केल |
| scale_y | **float** | Y स्केल |

### देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* क्लास [`IShape`](/slides/python-net/hi/aspose.slides/ishape)
* एन्यूमरेशन [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)