---
title: show_percentage property
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage प्रॉपर्टी
एक निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। 
True प्रतिशत मान प्रदर्शित करता है। False छिपाने के लिए। 
पढ़ें/लिखें **bool**।

### टिप्पणियाँ

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट एक DataLabelCollection डेटा लेबल का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल के लिए ShowPercentage प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त या सेट करता है। 
इस प्रॉपर्टी को मान के साथ सेट करने से यह मान DataLabelCollection संग्रह के सभी डेटा लेबल के लिए ShowPercentage प्रॉपर्टी पर भी सेट हो जाता है (उदा. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" कारण कि सभी DataLabels[i].ShowPercentage बराबर val हो जाता है)।

### परिभाषा:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### संबंधित देखें
* क्लास [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)