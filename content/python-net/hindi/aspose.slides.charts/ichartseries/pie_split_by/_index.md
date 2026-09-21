---
title: pie_split_by property
second_title: Aspose.Slides Python के लिए .NET API संदर्भ के माध्यम से
description: 
type: docs
url: /hi/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by प्रॉपर्टी
Specifies how to determine which data points are in the second pie or bar 
on a pie-of-pie or bar-of-pie chart.
This is the property not only of this series but of all series of parent series 
group - this is projection of appropriate group property. And so this property 
is read-only.
Use ParentSeriesGroup property for access to parent series group.
Use ParentSeriesGroup.PieSplitBy पढ़ने/लिखने की प्रॉपर्टी for change value.
केवल पढ़ने योग्य [`PieSplitType`](/slides/python-net/hi/aspose.slides.charts/piesplittype).

### टिप्पणियाँ
1) यह ParentSeriesGroup.PieSplitBy प्रॉपर्टी का प्रोजेक्शन है।
2) यदि प्रॉपर्टी मान PieSplitType.Custom है तो आप ParentSeriesGroup.PieSplitCustomPoints प्रॉपर्टी के साथ कस्टम विभाजन जानकारी परिभाषित कर सकते हैं।

### परिभाषा:
```python
@property
def pie_split_by(self):
    ...
```

### संबंधित देखें
* क्लास [`IChartSeries`](/slides/python-net/hi/aspose.slides.charts/ichartseries)
* एन्युमरेशन [`PieSplitType`](/slides/python-net/hi/aspose.slides.charts/piesplittype)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)