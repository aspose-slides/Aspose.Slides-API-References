---
title: show_percentage property
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage प्रॉपर्टी
निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। 
True प्रतिशत मान दिखाता है। False छिपाने के लिए। 
पढ़ें/लिखें **bool**।

### टिप्पणी
यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट एक DataLabelCollection डेटा लेबल्स का संग्रह है तो यह
प्रॉपर्टी नई डेटा लेबल्स के लिए DataLabelCollection संग्रह में ShowPercentage प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है।
इस प्रॉपर्टी को मान के साथ सेट करने से यह मान DataLabelCollection संग्रह में सभी डेटा लेबल्स के लिए ShowPercentage प्रॉपर्टी पर भी सेट हो जाता है
(उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" कारण बनता है कि 
सभी DataLabels[i].ShowPercentage मान val के बराबर हो जाता है)।

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
* क्लास [`DataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/datalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)