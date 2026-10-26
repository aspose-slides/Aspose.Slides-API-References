---
title: show_category_name property
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name प्रॉपर्टी
निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार का प्रतिनिधित्व करता है।
True को चार्ट पर डेटा लेबल के लिए श्रेणी नाम दिखाने के लिए सेट किया जाता है। False को छिपाने के लिए सेट किया जाता है।
पढ़ें/लिखें **bool**।

### टिप्पणी

यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowCategoryName प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान DataLabelCollection संग्रह में सभी डेटा लेबल्स की ShowCategoryName प्रॉपर्टी पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" के कारण सभी DataLabels[i].ShowCategoryName बराबर val हो जाता है)।

### परिभाषा:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### देखें भी
* क्लास [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)