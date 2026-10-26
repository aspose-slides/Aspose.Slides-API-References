---
title: show_label_as_data_callout property
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout प्रॉपर्टी
निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित किया जाएगा।

            यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट एक DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी DataLabelCollection संग्रह में नए डेटा लेबल्स के लिए ShowLabelAsDataCallout प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है।
            इस प्रॉपर्टी को मान के साथ सेट करने से यह मान DataLabelCollection संग्रह में सभी डेटा लेबल्स के लिए ShowLabelAsDataCallout प्रॉपर्टी पर भी सेट हो जाता है
            (उदा. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" के कारण सभी DataLabels[i].ShowLabelAsDataCallout बराबर val हो जाता है)।

### परिभाषा:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### देखें
* क्लास [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)