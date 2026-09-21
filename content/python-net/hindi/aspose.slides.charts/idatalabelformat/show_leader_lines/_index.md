---
title: show_leader_lines property
second_title: Aspose.Slides for Python के लिये .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines प्रॉपर्टी
निश्चित चार्ट के डेटा लेबल लीडर लाइन्स के प्रदर्शन व्यवहार को दर्शाता है। 
True लीडर लाइन्स को दिखाता है। False छिपाने के लिए। 
Read/write **bool**.

### टिप्पणियाँ

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी नए डेटा लेबल्स के लिए ShowLeaderLines प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त या सेट करती है। 
इस प्रॉपर्टी को मान के साथ सेट करने से यह मान DataLabelCollection संग्रह के सभी डेटा लेबल्स के ShowLeaderLines प्रॉपर्टी पर भी सेट हो जाता है 
(i.e. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" कारण से 
सभी DataLabels[i].ShowLeaderLines बराबर val हो जाता है)।

### परिभाषा:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### संबंधित देखें
* क्लास [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)