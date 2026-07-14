---
title: TrendlineCollection
second_title: Aspose.Slides for Android जावा API संदर्भ के माध्यम से
description: Trendline का एक संग्रह दर्शाता है
type: docs
url: /hi/com.aspose.slides/trendlinecollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफेस:**  
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)  
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Trendline का एक संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। |
| [add(int trendlineType)](#add-int-) | एक संग्रह के अंत में नया Trendline जोड़ता है और उसे लौटाता है। |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | निर्दिष्ट मान को हटाता है। |
| [iterator()](#iterator--) | एक enumerator लौटाता है जो संग्रह के माध्यम से इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java iterator लौटाता है। |
| [getCount()](#getCount--) | वास्तव में संग्रह में मौजूद तत्वों की संख्या प्राप्त करता है। |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

निर्दिष्ट अनुक्रमणिका पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [Trendline](../../com.aspose.slides/trendline)।

**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न मान:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

एक संग्रह के अंत में नया Trendline जोड़ता है और उसे लौटाता है।

**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| trendlineType | int |  |

**रिटर्न मान:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

निर्दिष्ट मान को हटाता है।

**परामितियाँ:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

एक enumerator लौटाता है जो संग्रह के माध्यम से इटरेट करता है।

**रिटर्न मान:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - एक IGenericEnumerator जिसका उपयोग संग्रह के माध्यम से इटरेट करने के लिए किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

पूरे संग्रह के लिए एक java iterator लौटाता है।

**रिटर्न मान:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - पूरे संग्रह के लिए एक java.util.Iterator।
### getCount() {#getCount--}
```
public final int getCount()
```

वास्तव में संग्रह में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न मान:**
int