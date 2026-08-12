---
title: get_SeriesGroup()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: 
type: docs
weight: 222
url: /hi/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) विधि



```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) विधि

निर्दिष्ट इंडेक्स पर श्रृंखला का समूह लौटाता है।

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## टिप्पणियाँ

1) प्रत्येक श्रृंखला समूह में संयोज्य प्रकार वाली श्रृंखलाएँ होती हैं। संयोज्य श्रृंखला प्रकारों के समूह CombinableSeriesTypesGroup enum के साथ परिभाषित और वर्णित किए गए हैं। साथ ही प्रत्येक श्रृंखला समूह में वह श्रृंखला होती है जो प्राथमिक अक्ष पर या द्वितीयक अक्ष पर प्लॉट की जाती है (एक ही समूह में दोनों मामलों में नहीं)। इसलिए, श्रृंखला समूह बनाने का सिद्धांत ऊपर उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा समूह बनाना है। 2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह की प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("series group properties")। [ChartSeriesGroup](../../chartseriesgroup/) क्लास में "Series group properties" पढ़ने/लिखने योग्य है। "series group properties" में से प्रत्येक का [ChartSeries](../../chartseries/) क्लास में केवल-पढ़ने योग्य प्रोजेक्शन हो सकता है।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartSeriesGroup](../../ichartseriesgroup/)
* क्लास [IChartSeries](../../ichartseries/)
* क्लास [IChartData](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)