---
title: position property
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## स्थिति प्रॉपर्टी
डेटा लेबल की स्थिति को दर्शाता है।
पढ़ने/लिखने योग्य [`LegendDataLabelPosition`](/slides/python-net/hi/aspose.slides.charts/legenddatalabelposition).


### टिप्पणियाँ

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबलों का संग्रह है तो यह प्रॉपर्टी नई डेटा लेबलों के लिए DataLabelCollection संग्रह में Position प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती या सेट करती है।
DataLabel ऑब्जेक्ट्स के लिए स्थिति को दर्शाता है।
इस प्रॉपर्टी को मान के साथ सेट करने से यह मान DataLabelCollection संग्रह में सभी डेटा लेबलों के लिए Position प्रॉपर्टी पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.Position = val;" के कारण सभी DataLabels[i].Position मान बराबर val हो जाता है)।

### परिभाषा:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```


### देखें
* क्लास [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat)
* एन्यूमरेशन [`LegendDataLabelPosition`](/slides/python-net/hi/aspose.slides.charts/legenddatalabelposition)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)