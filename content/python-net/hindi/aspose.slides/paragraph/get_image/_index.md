---
title: get_image method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image(self) {#}
पैराग्राफ की एक छवि लौटाता है।

### रिटर्न्स

एक छवि जिसमें render किया गया पैराग्राफ होता है, या **None**
             यदि पैराग्राफ अपने पैरेंट कलेक्शन में नहीं पाया जाता, वैध
             रेंडरिंग बाउंड्स नहीं है, या छवि को render करते समय कोई त्रुटि आती है।



```python
def get_image(self):
    ...
```



## get_image(self, scale_x, scale_y) {#float-float}
निर्दिष्ट स्केल के साथ पैराग्राफ की एक छवि लौटाता है।

### रिटर्न्स

एक छवि जिसमें render किया गया पैराग्राफ होता है, या **None**
             यदि पैराग्राफ अपने पैरेंट कलेक्शन में नहीं पाया जाता, वैध
             रेंडरिंग बाउंड्स नहीं है, या छवि को render करते समय कोई त्रुटि आती है।



```python
def get_image(self, scale_x, scale_y):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scale_x | **float** | पैराग्राफ छवि पर लागू किया गया क्षैतिज स्केल फैक्टर। |
| scale_y | **float** | पैराग्राफ छवि पर लागू किया गया ऊर्ध्वाधर स्केल फैक्टर। |



### देखें
* क्लास [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* क्लास [`Paragraph`](/slides/python-net/hi/aspose.slides/paragraph)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)