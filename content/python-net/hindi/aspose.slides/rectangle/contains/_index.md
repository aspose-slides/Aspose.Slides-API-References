---
title: contains method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
निर्धारित करता है कि निर्दिष्ट बिंदु इस आयत में शामिल है या नहीं।

### रिटर्न
`True` यदि बिंदु इस आयत में शामिल है; अन्यथा, `False`.



```python
def contains(self, point):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/hi/aspose.slides/point) | परीक्षण के लिए बिंदु। `x` और `y` गुणों वाले कोई भी वस्तु स्वीकार्य है। |

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| **TypeError** | तर्कों की संख्या गलत है। |


## contains(self, rect) {#rectangle}
निर्धारित करता है कि `rect` द्वारा प्रतिनिधित्व किया गया आयताकार क्षेत्र इस आयत में पूरी तरह से सम्मिलित है या नहीं।

### रिटर्न
`True` यदि `rect` द्वारा प्रतिनिधित्व किया गया आयताकार क्षेत्र इस आयत में पूरी तरह से सम्मिलित है; अन्यथा, `False`.



```python
def contains(self, rect):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/hi/aspose.slides/rectangle) | परीक्षण के लिए आयत। `x`, `y`, `width` और `height` गुणों वाले कोई भी वस्तु स्वीकार्य है। |

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| **TypeError** | तर्कों की संख्या गलत है। |


## contains(self, x, y) {#int-int}
निर्धारित करता है कि निर्दिष्ट बिंदु इस आयत में शामिल है या नहीं।

### रिटर्न
`True` यदि `x` और `y` द्वारा परिभाषित बिंदु इस आयत में शामिल है; अन्यथा, `False`.



```python
def contains(self, x, y):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **int** | परीक्षण के बिंदु का x-निर्देशांक। |
| y | **int** | परीक्षण के बिंदु का y-निर्देशांक। |

### अपवाद
| अपवाद | विवरण |
| :- | :- |
| **TypeError** | तर्कों की संख्या गलत है। |



### देखें
* क्लास [`Point`](/slides/python-net/hi/aspose.slides/point)
* क्लास [`Rectangle`](/slides/python-net/hi/aspose.slides/rectangle)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)