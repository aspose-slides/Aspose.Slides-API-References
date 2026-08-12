---
title: get_SeriesGroups()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: श्रृंखला के समूह प्राप्त करता है। केवल-पढ़ने योग्य IChartSeriesGroupCollection.
type: docs
weight: 27
url: /hi/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() विधि

श्रृंखला के समूह प्राप्त करता है। केवल-पढ़ने योग्य [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## टिप्पणियाँ

1) प्रत्येक श्रृंखला समूह में संयोज्य प्रकारों वाली श्रृंखलाएँ होती हैं। संयोज्य श्रृंखला प्रकारों के समूह CombinableSeriesTypesGroup enum के साथ परिभाषित और वर्णित किए गए हैं। साथ ही प्रत्येक श्रृंखला समूह में ऐसी श्रृंखलाएँ होती हैं जो मुख्य अक्ष या द्वितीयक अक्ष पर प्लॉट की जाती हैं (एक ही समूह में दोनों नहीं)। इसलिए, श्रृंखला समूह बनाने का सिद्धांत उपरोक्त उल्लेखित प्रकार समूहों और मुख्य/द्वितीयक प्लॉटिंग प्रकार द्वारा समूहबद्ध करना है।

2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह की प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("series group properties")। [ChartSeriesGroup](../../chartseriesgroup/) क्लास में "Series group properties" पढ़ें/लिखें है। प्रत्येक "series group properties" का केवल-पढ़ने योग्य प्रोजेक्शन [ChartSeries](../../chartseries/) क्लास में हो सकता है।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* क्लास [IChartData](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)