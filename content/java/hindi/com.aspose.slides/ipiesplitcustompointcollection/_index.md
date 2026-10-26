---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides for Java API संदर्भ
description: कस्टम स्प्लिट के साथ बार-ऑफ़-पाई या पाई-ऑफ़-पाई चार्ट में दूसरे पाई या बार पर ड्रॉ किए जाने वाले बिंदुओं का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ipiesplitcustompointcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

दूसरे पाई या बार पर बार-ऑफ़-पाई या पाई-ऑफ़-पाई चार्ट में कस्टम स्प्लिट के साथ ड्रॉ किए जाने वाले बिंदुओं का संग्रह दर्शाता है।
## Methods

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा चार्ट डेटा बिंदु लौटाता है। |
| [add(int dataPointIndex)](#add-int-) | पैरेंट सीरीज़ पॉइंट संग्रह में उसके इंडेक्स द्वारा डेटा पॉइंट जोड़ता है। |
| [remove(int dataPointIndex)](#remove-int-) | पैरेंट सीरीज़ पॉइंट संग्रह में उसके इंडेक्स द्वारा आइटम को संग्रह से हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


इंडेक्स द्वारा चार्ट डेटा बिंदु लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डेटा-पॉइंट का इंडेक्स। |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - चार्ट डेटा बिंदु।
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


पैरेंट सीरीज़ पॉइंट संग्रह में उसके इंडेक्स द्वारा डेटा पॉइंट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPointIndex | int | पैरेंट सीरीज़ पॉइंट संग्रह में डेटा पॉइंट का इंडेक्स। |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


पैरेंट सीरीज़ पॉइंट संग्रह में उसके इंडेक्स द्वारा आइटम को संग्रह से हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPointIndex | int | पैरेंट सीरीज़ पॉइंट संग्रह में डेटा पॉइंट का इंडेक्स। |