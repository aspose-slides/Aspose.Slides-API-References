---
title: show_series_name property
second_title: Aspose.Slides Python के लिए via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name प्रॉपर्टी
एक Boolean को लौटाता है या सेट करता है ताकि चार्ट पर डेटा लेबल्स के लिए श्रृंखला नाम दिखाने के व्यवहार को दर्शाया जा सके। 
            True सेट करने पर श्रृंखला नाम दिखेगा। False सेट करने पर छिपा रहेगा।
            पढ़ें/लिखें **bool**.

### टिप्पणी

यदि इस DataLabelFormat वस्तु का मूल (parent) एक DataLabelCollection डेटा लेबल्स का संग्रह है तो यह
            प्रॉपर्टी नई डेटा लेबल्स के लिए DataLabelCollection संग्रह में ShowSeriesName प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त या सेट करती है।
            इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी DataLabelCollection संग्रह में डेटा लेबल्स की ShowSeriesName प्रॉपर्टी पर भी सेट हो जाता है
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" cause to 
            all DataLabels[i].ShowSeriesName is equal to val).

### परिभाषा:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### देखें
* क्लास [`DataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/datalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)