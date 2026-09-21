---
title: show_category_name property
second_title: Aspose.Slides for Python द्वारा .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name प्रॉपर्टी
एक निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार का प्रतिनिधित्व करता है।
चार्ट पर डेटा लेबल के लिए श्रेणी नाम प्रदर्शित करने हेतु True. छुपाने के लिए False.
पढ़ें/लिखें **bool**.

### टिप्पणी

यदि इस DataLabelFormat वस्तु का अभिभावक डेटा लेबल्स का DataLabelCollection संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowCategoryName प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त या सेट करती है।
इस प्रॉपर्टी को मान के साथ सेट करने से यह मान DataLabelCollection संग्रह में सभी डेटा लेबल्स के लिए ShowCategoryName प्रॉपर्टी पर भी सेट हो जाता है।
(i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" सभी DataLabels[i].ShowCategoryName को val के बराबर बनाता है)।

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
* क्लास [`DataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/datalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)