---
title: get_image method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
एक पैराग्राफ की छवि लौटाता है।

### रिटर्न
एक छवि जिसमें रेंडर किया गया पैराग्राफ शामिल है, या **None** यदि पैराग्राफ उसके पैरेंट संग्रह में नहीं मिला, कोई वैध रेंडरिंग सीमा नहीं है, या छवि रेंडर करते समय त्रुटि आती है।

```python
def get_image(self):
    ...
```

## get_image {#float-float}
निर्दिष्ट स्केल के साथ पैराग्राफ की छवि लौटाता है।

### रिटर्न
एक छवि जिसमें रेंडर किया गया पैराग्राफ शामिल है, या **None** यदि पैराग्राफ उसके पैरेंट संग्रह में नहीं मिला, कोई वैध रेंडरिंग सीमा नहीं है, या छवि रेंडर करते समय त्रुटि आती है।

```python
def get_image(self, scale_x, scale_y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | पैराग्राफ छवि पर लागू होने वाला क्षैतिज स्केल फैक्टर। |
| scale_y | **float** | पैराग्राफ छवि पर लागू होने वाला लंबवत स्केल फैक्टर। |

### देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* क्लास [`Paragraph`](/slides/python-net/hi/aspose.slides/paragraph)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)