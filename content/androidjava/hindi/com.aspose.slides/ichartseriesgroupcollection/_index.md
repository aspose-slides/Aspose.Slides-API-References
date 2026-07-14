---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: संयोज्य श्रृंखलाओं के समूहों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartseriesgroupcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

संयोज्य श्रृंखलाओं के समूहों का संग्रह दर्शाता है।

--------------------

1) प्रत्येक श्रृंखला समूह में संयोज्य प्रकारों वाली श्रृंखलाएँ होती हैं। संयोज्य श्रृंखला प्रकारों के समूह CombinableSeriesTypesGroup enum द्वारा परिभाषित और वर्णित हैं। साथ ही प्रत्येक श्रृंखला समूह में ऐसी श्रृंखलाएँ होती हैं जो प्राथमिक अक्ष पर या द्वितीयक अक्ष पर प्लॉट की जाती हैं (एक ही समूह में दोनों मामलों नहीं)। इसलिए, श्रृंखला समूह बनाने का सिद्धांत ऊपर उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार द्वारा समूह बनाना है। 2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह में प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("series group properties")। ChartSeriesGroup क्लास में "Series group properties" पढ़ने/लिखने योग्य हैं। प्रत्येक "series group properties" का एक केवल-पढ़ने योग्य प्रोजेक्शन ChartSeries क्लास में हो सकता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | सीरीज़ द्वारा श्रृंखला समूह प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | सूचकांक द्वारा श्रृंखला समूह प्राप्त करता है। |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

सीरीज़ द्वारा श्रृंखला समूह प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**रिटर्न:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

सूचकांक द्वारा श्रृंखला समूह प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)