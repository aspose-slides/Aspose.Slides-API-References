---
title: number_format property
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format प्रॉपर्टी
DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है।
            पढ़ें/लिखें **str**.

### टिप्पणियाँ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this
            property gets or sets the default value of the NumberFormat property for the new data 
            labels in the DataLabelCollection collection.
            When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" causes all DataLabels[i].NumberFormat to equal to val).

### परिभाषा:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### संबंधित देखें
* क्लास [`IDataLabelFormat`](/slides/python-net/hi/aspose.slides.charts/idatalabelformat)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)