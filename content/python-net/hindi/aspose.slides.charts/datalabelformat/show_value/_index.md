---
title: show_value property
second_title: Aspose.Slides Python के लिए .NET API रेफरेंस के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value प्रॉपर्टी
निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार को दर्शाता है। 
True प्रतिशत मान प्रदर्शित करता है। False छिपाने के लिए। 
पढ़ें/लिखें **bool**.

### टिप्पणियाँ
यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट एक DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी नई डेटा लेबल्स के लिए DataLabelCollection संग्रह में ShowValue प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती या सेट करती है।  
इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के लिए DataLabelCollection संग्रह में ShowValue प्रॉपर्टी पर भी सेट हो जाता है।  
(i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause to all DataLabels[i].ShowValue is equal to val).

### परिभाषा:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### देखें
* क्लास [`DataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/datalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)