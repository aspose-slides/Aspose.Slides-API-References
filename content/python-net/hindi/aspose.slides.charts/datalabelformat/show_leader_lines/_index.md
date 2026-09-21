---
title: show_leader_lines property
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines प्रॉपर्टी
निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइनों की प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। 
True लीडर लाइनों को प्रदर्शित करता है। False छिपाने के लिए। 
पढ़ें/लिखें **bool**.

### टिप्पणियाँ
यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLeaderLines प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती या सेट करती है। इस प्रॉपर्टी को मान सहित सेट करने से यह मान DataLabelCollection संग्रह में सभी डेटा लेबल्स के लिए ShowLeaderLines प्रॉपर्टी पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" सभी DataLabels[i].ShowLeaderLines को val के समान बनाता है)।

### परिभाषा:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### संबंधित
* क्लास [`DataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/datalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)