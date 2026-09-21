---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection क्लास

संयोज्य श्रृंखलाओं के समूहों के संग्रह का प्रतिनिधित्व करता है।

IChartSeriesGroupCollection प्रकार निम्नलिखित सदस्यों को प्रस्तुत करता है:

इंडेक्स द्वारा श्रृंखला समूह प्राप्त करता है।

## इंडेक्सर

| नाम | विवरण |
| :- | :- |
| [`[index]`](/slides/python-net/hi/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### टिप्पणी

1) प्रत्येक श्रृंखला समूह में संयोज्य प्रकारों वाली श्रृंखलाएँ होती हैं। संयोज्य श्रृंखला प्रकारों के समूह CombinableSeriesTypesGroup enum द्वारा परिभाषित और वर्णित हैं। साथ ही प्रत्येक श्रृंखला समूह में ऐसी श्रृंखलाएँ होती हैं जो प्रमुख अक्ष या द्वितीयक अक्ष पर प्लॉट की जाती हैं (एक ही समूह में दोनों मामलों में नहीं)। इसलिए, श्रृंखला समूह बनाना ऊपर उल्लेखित प्रकार समूहों और प्रमुख/द्वितीयक प्लॉटिंग प्रकार द्वारा समूह बनाना है।

2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह की प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("series group properties")। "Series group properties" ChartSeriesGroup क्लास में read/write है। ChartSeries क्लास में प्रत्येक "series group properties" का read-only प्रोजेक्शन हो सकता है।


### देखें अन्य
* मॉड्यूल [`aspose.slides.charts`](/slides/python-net/hi/aspose.slides.charts)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)