---
title: show_series_name property
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name प्रॉपर्टी
एक Boolean को लौटाता है या सेट करता है ताकि चार्ट पर डेटा लेबल्स के लिए सीरीज़ नाम प्रदर्शित करने के व्यवहार को दर्शाया जा सके। 
            True को सेट करने पर सीरीज़ नाम दिखाया जाता है। False को सेट करने पर छिपाया जाता है। 
            पढ़ने/लिखने **bool**.


### टिप्पणियाँ

यदि इस DataLabelFormat वस्तु का पैरेंट एक DataLabelCollection डेटा लेबल्स का संग्रह है तो यह
            प्रॉपर्टी नया डेटा लेबल्स के लिए ShowSeriesName प्रॉपर्टी का डिफॉल्ट मान प्राप्त करती है या सेट करती है 
            DataLabelCollection संग्रह में लेबल्स।
            इस प्रॉपर्टी को मान के साथ सेट करने से यह मान ShowSeriesName प्रॉपर्टी को भी सेट करता है 
            DataLabelCollection संग्रह के सभी डेटा लेबल्स के लिए
            (उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" 
            सभी DataLabels[i].ShowSeriesName मान val के बराबर हो जाता है)।

### परिभाषा:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### और देखें
* वर्ग [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)