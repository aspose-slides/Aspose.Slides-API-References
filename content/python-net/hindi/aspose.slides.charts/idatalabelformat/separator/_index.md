---
title: separator property
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## सेपरेटर प्रॉपर्टी
एक Variant सेट करता है या लौटाता है जो चार्ट पर डेटा लेबल्स के लिए उपयोग किए जाने वाले सेपरेटर को दर्शाता है।
पढ़ें/लिखें **str**.


### टिप्पणियाँ

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट एक DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए Separator प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती या सेट करती है।  
इस प्रॉपर्टी को मान के साथ सेट करने से यह मान DataLabelCollection संग्रह में सभी डेटा लेबल्स की Separator प्रॉपर्टी को भी सेट करता है (उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.Separator = val;" जिससे सभी DataLabels[i].Separator इस मान के बराबर हो जाते हैं)।

### परिभाषा:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### संबंधित देखें
* क्लास [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)