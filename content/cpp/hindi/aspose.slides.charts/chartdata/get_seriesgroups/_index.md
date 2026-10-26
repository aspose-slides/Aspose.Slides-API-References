---
title: get_SeriesGroups()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: श्रृंखलाओं के समूह प्राप्त करता है। केवल पढ़ने योग्य IChartSeriesGroupCollection.
type: docs
weight: 27
url: /hi/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() मेथड


श्रृंखलाओं के समूह प्राप्त करता है। केवल पढ़ने योग्य [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)।

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## टिप्पणी


1) प्रत्येक श्रृंखला समूह में संयोज्य प्रकारों वाली श्रृंखलाएँ होती हैं। संयोज्य श्रृंखला प्रकारों के समूह CombinableSeriesTypesGroup enum द्वारा परिभाषित और वर्णित हैं। साथ ही प्रत्येक श्रृंखला समूह में ऐसी श्रृंखलाएँ होती हैं जो प्राथमिक अक्ष पर या द्वितीयक अक्ष पर प्लॉट की जाती हैं (एक ही समूह में दोनों मामलों को नहीं)। इसलिए, श्रृंखला समूहण का सिद्धांत उपरोक्त उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा समूह बनाना है।

2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह में प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("series group properties")। "Series group properties" [ChartSeriesGroup](../../chartseriesgroup/) क्लास में पढ़ने/लिखने योग्य है। "Series group properties" में से प्रत्येक का [ChartSeries](../../chartseries/) क्लास में केवल पढ़ने योग्य प्रोजेक्शन हो सकता है। 

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* क्लास [ChartData](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)