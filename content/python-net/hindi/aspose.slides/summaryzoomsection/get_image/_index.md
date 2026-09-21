---
title: get_image method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/summaryzoomsection/get_image/
weight: 30
---
## get_image(self) {#}
shape थंबनेल लौटाता है।
            ShapeThumbnailBounds.Shape shape thumbnail bounds type डिफ़ॉल्ट रूप से उपयोग किया जाता है।

### वापसी

Shape थंबनेल।

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
shape थंबनेल लौटाता है।

### वापसी

Shape थंबनेल या None यदि ShapeThumbnailBounds.Appearance का उपयोग किया गया हो और shape में दृश्यमान तत्व न हों।

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds) | Shape थंबनेल बाउंड्स प्रकार। |
| scale_x | **float** | X स्केल |
| scale_y | **float** | Y स्केल |

### देखें भी
* वर्ग [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* एन्यूमरेशन [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds)
* वर्ग [`SummaryZoomSection`](/slides/python-net/hi/aspose.slides/summaryzoomsection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)