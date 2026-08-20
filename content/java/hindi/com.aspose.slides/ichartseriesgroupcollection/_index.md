---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides जावा API संदर्भ
description: संयोजनीय श्रृंखलाओं के समूहों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartseriesgroupcollection/
---
**सभी लागू इंटरफ़ेस:**  
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

संयोजनीय सीरीज के समूहों का संग्रह दर्शाता है।

--------------------

1) प्रत्येक सीरीज समूह में संयोजनीय प्रकारों की सीरीज शामिल होती हैं। CombinableSeriesTypesGroup enum के साथ परिभाषित और वर्णित संयोजनीय सीरीज प्रकारों के समूह। 또한 प्रत्येक सीरीज समूह में ऐसी सीरीज होती हैं जो प्राथमिक अक्ष या द्वितीयक अक्ष पर प्लॉट की जाती हैं (एक ही समूह में दोनों मामलों नहीं)। इसलिए, सीरीज समूह बनाने का सिद्धांत ऊपर उल्लेखित प्रकार समूहों और प्राथमिक/द्वितीयक प्लॉटिंग प्रकार के अनुसार समूह बनाना है। 2) सीरीज समूह में कुछ सीरीज गुण होते हैं जो समूह की प्रत्येक सीरीज के लिए सामान्य होते हैं ("series group properties"). "Series group properties" ChartSeriesGroup क्लास में पढ़ने/लिखने योग्य है। प्रत्येक "series group properties" की एक केवल-पढ़ने योग्य प्रोजेक्शन ChartSeries क्लास में हो सकती है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | सीरीज के द्वारा सीरीज समूह प्राप्त करता है। |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स के द्वारा सीरीज समूह प्राप्त करता है। |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

सीरीज के द्वारा सीरीज समूह प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**वापसी:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

इंडेक्स के द्वारा सीरीज समूह प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)