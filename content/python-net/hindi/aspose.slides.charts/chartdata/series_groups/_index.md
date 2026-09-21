---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups गुण
सीरीज के समूह प्राप्त करता है।
केवल पढ़ने योग्य [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection).

### टिप्पणियाँ

1) प्रत्येक सीरीज समूह में संयोज्य प्रकार वाली सीरीज होती हैं। 
            CombinableSeriesTypesGroup एनोम के साथ संयोज्य सीरीज प्रकारों के समूह को परिभाषित और वर्णित किया गया है। 
            साथ ही प्रत्येक सीरीज समूह में ऐसी सीरीज होती हैं जो प्राथमिक अक्षों या द्वितीयक अक्षों पर प्लॉट की जाती हैं (एक ही समूह में दोनों नहीं)। 
            इसलिए, सीरीज समूहिंग का सिद्धांत ऊपर उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार के आधार पर समूह बनाना है।

2) सीरीज समूह में कुछ सीरीज गुण होते हैं जो समूह की प्रत्येक सीरीज के लिए सामान्य होते हैं ("series group properties")। 
            "Series group properties" ChartSeriesGroup क्लास में पढ़ना/लिखना संभव है। 
            प्रत्येक "series group properties" का एक केवल पढ़ने योग्य प्रोजेक्शन ChartSeries क्लास में हो सकता है।

### परिभाषा:
```python
@property
def series_groups(self):
    ...
```

### See Also
* क्लास [`ChartData`](/slides/python-net/hi/aspose.slides.charts/chartdata)
* क्लास [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)