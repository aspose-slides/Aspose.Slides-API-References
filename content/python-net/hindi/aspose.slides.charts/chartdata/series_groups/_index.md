---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups प्रॉपर्टी
सीरीज़ के समूह प्राप्त करता है।  
केवल पढ़ने योग्य [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection)।

### टिप्पणियाँ

1) प्रत्येक सीरीज़ समूह में संयोज्य प्रकारों वाली सीरीज़ शामिल होती है। संयोज्य सीरीज़ प्रकारों के समूह को CombinableSeriesTypesGroup enum के साथ परिभाषित और वर्णित किया गया है। साथ ही प्रत्येक सीरीज़ समूह में ऐसी सीरीज़ शामिल हैं जो प्राथमिक अक्षों या द्वितीयक अक्षों पर प्लॉट की जाती हैं (एक ही समूह में दोनों मामलों में नहीं)। इसलिए, सीरीज़ ग्रुपिंग का सिद्धांत ऊपर उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा समूह बनाना है।

2) सीरीज़ समूह में कुछ सीरीज़ प्रॉपर्टीज़ होती हैं जो समूह में प्रत्येक सीरीज़ के लिए सामान्य होती हैं ("सीरीज़ समूह गुण")। "सीरीज़ समूह गुण" ChartSeriesGroup क्लास में पढ़ने/लिखने योग्य है। "सीरीज़ समूह गुण" में से प्रत्येक का ChartSeries क्लास में केवल पढ़ने योग्य प्रोजेक्शन हो सकता है।

### परिभाषा:
```python
@property
def series_groups(self):
    ...
```

### संबंधित देखें
* क्लास [`ChartData`](/slides/python-net/hi/aspose.slides.charts/chartdata)
* क्लास [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)