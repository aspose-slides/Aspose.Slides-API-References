---
title: ITrendlineCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: TrendlineEx का संग्रह दर्शाता है
type: docs
url: /hi/com.aspose.slides/itrendlinecollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

TrendlineEx का संग्रह दर्शाता है
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [getCount()](#getCount--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [add(int trendlineType)](#add-int-) | संग्रह के अंत में नया Trendline जोड़ता है और उसे लौटाता है। |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | निर्दिष्ट मान को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [ITrendline](../../com.aspose.slides/itrendline)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


संग्रह के अंत में नया Trendline जोड़ता है और उसे लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| trendlineType | int | Trendline प्रकार [TrendlineType](../../com.aspose.slides/trendlinetype) |

**रिटर्न:**
[ITrendline](../../com.aspose.slides/itrendline) - नया Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


निर्दिष्ट मान को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | हटाने के लिए Trendline [ITrendline](../../com.aspose.slides/itrendline) |