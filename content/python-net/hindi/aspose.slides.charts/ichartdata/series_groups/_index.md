---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups संपत्ति
Gets the groups of series.
केवल-पढ़ने योग्य [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection).

### टिप्पणी
1) प्रत्येक series समूह में combinable प्रकारों वाली series होती हैं। combinable series प्रकारों के समूह CombinableSeriesTypesGroup enum द्वारा परिभाषित और वर्णित किए गए हैं। इसके अलावा प्रत्येक series समूह में ऐसी series होती हैं जो primary axes या secondary axes पर plotted होती हैं (एक ही समूह में दोनों नहीं)। इसलिए, series grouping का सिद्धांत ऊपर उल्लेखित प्रकार समूहों और primary/secondary plotting प्रकार द्वारा समूह बनाना है।

2) series समूह में कुछ series properies होते हैं जो समूह की प्रत्येक series में सामान्य होते हैं ("series group properties")। "Series group properties" ChartSeriesGroup क्लास में पढ़ने/लिखने योग्य है। प्रत्येक "series group properties" का एक केवल-पढ़ने योग्य projection ChartSeries क्लास में हो सकता है।

### परिभाषा:
```python
@property
def series_groups(self):
    ...
```

### देखें
* क्लास [`IChartData`](/slides/python-net/hi/aspose.slides.charts/ichartdata)
* क्लास [`IChartSeriesGroupCollection`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection)
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)