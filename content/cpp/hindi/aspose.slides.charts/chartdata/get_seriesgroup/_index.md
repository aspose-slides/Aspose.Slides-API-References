---
title: get_SeriesGroup()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: 
type: docs
weight: 222
url: /hi/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) विधि




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) विधि


निर्दिष्ट सूचकांक पर श्रृंखला का समूह लौटाता है।

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## टिप्पणियाँ


1) श्रृंखला के प्रत्येक समूह में संयोज्य प्रकारों वाली श्रृंखलाएँ होती हैं। CombinableSeriesTypesGroup enum के साथ संयोज्य श्रृंखला प्रकारों के समूह परिभाषित और वर्णित किए जाते हैं। इसके अलावा प्रत्येक श्रृंखला समूह में ऐसी श्रृंखलाएँ होती हैं जो प्राथमिक अक्षों या द्वितीयक अक्षों पर प्लॉट की जाती हैं (एक समूह में दोनों मामलों को नहीं)। इस प्रकार, श्रृंखला समूह बनाने का सिद्धांत ऊपर उल्लिखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार के आधार पर समूह बनाना है। 2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह में प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("series group properties")। "Series group properties" [ChartSeriesGroup](../../chartseriesgroup/) class में read/write है। प्रत्येक "series group properties" का [ChartSeries](../../chartseries/) class में पढ़ने-केवल (read-only) प्रोजेक्शन हो सकता है। 

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroup](../../ichartseriesgroup/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)