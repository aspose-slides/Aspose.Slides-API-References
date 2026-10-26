---
title: get_image method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
आकार थंबनेल लौटाता है।
            ShapeThumbnailBounds.Shape shape thumbnail bounds type डिफ़ॉल्ट रूप से उपयोग किया जाता है।

### वापसी

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
आकार थंबनेल लौटाता है।

### वापसी

Shape thumbnail या None यदि ShapeThumbnailBounds.Appearance उपयोग किया जाता है और आकार में दृश्यमान तत्व नहीं हैं।

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X स्केल |
| scale_y | **float** | Y स्केल |

### संबंधित देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* एन्यूमरेशन [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds)
* क्लास [`SmartArt`](/slides/python-net/hi/aspose.slides.smartart/smartart)
* मॉड्यूल [`aspose.slides.smartart`](/slides/python-net/hi/aspose.slides.smartart)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)