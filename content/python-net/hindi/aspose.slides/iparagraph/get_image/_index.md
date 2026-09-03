---
title: get_image method
second_title: Aspose.Slides Python के लिये .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
एक पैराग्राफ की छवि लौटाता है।

### रिटर्न
एक छवि जिसमें रेंडर किया गया पैराग्राफ हो, या **None** यदि पैराग्राफ को इसके मूल संग्रह में नहीं पाया जा सके, उसका वैध रेंडरिंग बाउंड नहीं हो, या छवि रेंडर करते समय कोई त्रुटि हो।



```python
def get_image(self):
    ...
```



## get_image {#float-float}
निर्दिष्ट स्केल के साथ पैराग्राफ की छवि लौटाता है।

### रिटर्न
एक छवि जिसमें रेंडर किया गया पैराग्राफ हो, या **None** यदि पैराग्राफ को इसके मूल संग्रह में नहीं पाया जा सके, उसका वैध रेंडरिंग बाउंड नहीं हो, या छवि रेंडर करते समय कोई त्रुटि हो।



```python
def get_image(self, scale_x, scale_y):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scale_x | **float** | पैराग्राफ छवि पर लागू क्षैतिज स्केल फैक्टर। |
| scale_y | **float** | पैराग्राफ छवि पर लागू लंबवत स्केल फैक्टर। |



### देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* क्लास [`IParagraph`](/slides/python-net/hi/aspose.slides/iparagraph)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)