---
title: separator property
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## separator प्रॉपर्टी
Sets or returns a Variant representing the separator used for the data labels on a chart.
            पढ़ें/लिखें **str**.


### टिप्पणियाँ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this प्रॉपर्टी gets or sets the default value of the Separator प्रॉपर्टी for the new data labels in the DataLabelCollection collection.
            Set this प्रॉपर्टी with value also sets this value to the Separator प्रॉपर्टी 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Separator = val;" cause to 
            all DataLabels[i].Separator is equal to val).

### परिभाषा:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### देखें भी
* क्लास [`DataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/datalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)