---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups गुण
सीरीज़ के समूह प्राप्त करता है।
केवल पढ़ने योग्य [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection).

### टिप्पणी
1) प्रत्येक सीरीज़ समूह में संयोज्य प्रकारों वाली सीरीज़ शामिल होती हैं। संयोज्य सीरीज़ प्रकारों के समूह को CombinableSeriesTypesGroup enum के साथ परिभाषित और वर्णित किया गया है। साथ ही प्रत्येक सीरीज़ समूह में वह सीरीज़ शामिल होती है जो प्राथमिक अक्ष पर या द्वितीयक अक्ष पर प्लॉट की जाती है (एक ही समूह में दोनों मामलों नहीं)। इसलिए, सीरीज़ समूहकरण का सिद्धांत ऊपर उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा समूह बनाना है।

2) सीरीज़ का समूह कुछ सीरीज़ प्रॉपर्टी रखता है जो समूह में प्रत्येक सीरीज़ के लिए सामान्य होती हैं ("series group properties")। "Series group properties" ChartSeriesGroup class में पढ़ें/लिखें योग्य है। प्रत्येक "series group properties" का एक केवल पढ़ने योग्य प्रोजेक्शन ChartSeries class में हो सकता है।

### परिभाषा:
```python
@property
def series_groups(self):
    ...
```

### संबंधित देखें
* क्लास [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* क्लास [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)