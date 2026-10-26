---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides का Android के लिए Java API संदर्भ
description: एक कस्टम स्प्लिट के साथ बार-ऑफ़-पाई या पाई-ऑफ़-पाई चार्ट में दूसरी पाई या बार में खींचे जाने वाले बिंदुओं का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ipiesplitcustompointcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Represents a collection of points that shall be drawn in the second pie or bar on a bar-of-pie or pie-of-pie chart with a custom split.
## विधियां

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा चार्ट डेटा पॉइंट लौटाता है। |
| [add(int dataPointIndex)](#add-int-) | पैरेंट सीरीज़ पॉइंट्स कलेक्शन में उसके इंडेक्स से डेटा पॉइंट जोड़ता है। |
| [remove(int dataPointIndex)](#remove-int-) | पैरेंट सीरीज़ पॉइंट्स कलेक्शन में उसके इंडेक्स से आइटम को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

इंडेक्स द्वारा चार्ट डेटा पॉइंट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डेटा-पॉइंट का इंडेक्स। |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - चार्ट डेटा पॉइंट।

### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

पैरेंट सीरीज़ पॉइंट्स कलेक्शन में उसके इंडेक्स से डेटा पॉइंट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPointIndex | int | पैरेंट सीरीज़ पॉइंट्स कलेक्शन में डेटा पॉइंट का इंडेक्स। |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

पैरेंट सीरीज़ पॉइंट्स कलेक्शन में उसके इंडेक्स से आइटम को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPointIndex | int | पैरेंट सीरीज़ पॉइंट्स कलेक्शन में डेटा पॉइंट का इंडेक्स.. |