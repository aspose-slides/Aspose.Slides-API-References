---
title: TrendlineCollection
second_title: Java के लिए Aspose.Slides API संदर्भ
description: Trendline का एक संग्रह दर्शाता है
type: docs
url: /hi/com.aspose.slides/trendlinecollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Trendline का संग्रह दर्शाता है
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(int trendlineType)](#add-int-) | Adds the new Trendline at the end of a collection and return it. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Removes the specified value. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल पढ़ने योग्य [Trendline](../../com.aspose.slides/trendline).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

एक संग्रह के अंत में नया Trendline जोड़ता है और उसे लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| trendlineType | int |  |

**रिटर्न:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

निर्दिष्ट मान को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

एक enumerator लौटाता है जो संग्रह के माध्यम से इटरेट करता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

संपूर्ण संग्रह के लिए java iterator लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - एक java.iterator जो संपूर्ण संग्रह के लिए है।
### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int