---
title: show_legend_key property
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key प्रॉपर्टी
एक निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। 
True if the data label legend key is visible.
पढ़ें/लिखें **bool**.

### टिप्पणी
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            प्रॉपर्टी gets or sets the default value of the ShowLegendKey प्रॉपर्टी for the new data 
            लेबलों in the DataLabelCollection collection.
            Set this प्रॉपर्टी with value also sets this value to the ShowLegendKey प्रॉपर्टी 
            for सभी data लेबलों in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" कारण 
            सभी DataLabels[i].ShowLegendKey is equal to val).

### परिभाषा:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### देखें
* क्लास [`DataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/datalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)