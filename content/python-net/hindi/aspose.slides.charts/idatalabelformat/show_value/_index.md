---
title: show_value property
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value प्रॉपर्टी
एक निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। 
True प्रतिशत मान को दिखाता है। False छिपाने के लिए। 
पढ़ें/लिखें **bool**.

### टिप्पणी

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट एक DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowValue प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। 
इस प्रॉपर्टी को मान के साथ सेट करने से यह मान DataLabelCollection संग्रह में सभी डेटा लेबल्स की ShowValue प्रॉपर्टी में भी सेट हो जाता है। 
(उदा. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" सभी DataLabels[i].ShowValue को val के बराबर कर देता है।)

### परिभाषा:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### देखें भी
* क्लास [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)